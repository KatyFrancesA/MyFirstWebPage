# MyFirstWebPage
Created using Career Foundry tutorial 

body {
    background-color: #f0fcff;
  }
  body {
    color: #001f3f;
  }
  body {
    font-family: 'Noto Sans', sans-serif;
  }
h1, h2, h3, h4 {
    font-family: 'Roboto Mono', monospace;
  }
.container {
    max-width: 840px;
    margin: 0 auto;
}
.intro {
    text-align: center;
}
.quote {
    font-style: italic;
}

.about-grid {
    display: grid;
    grid-template-columns: 50% 50%;
}
.i-am, .i-like {
    text-align: center;
    text-decoration: none;
}
.about-list {
    list-style: none;
    padding: 0;
}
@media (max-width: 480px) {
    .about-grid {
        grid-template-columns: 100%;
    }
}
.projects-heading {
    text-align: center;
}
.projects-grid {
    display: grid;
    grid-template-columns: 50% 50%;
    column-gap: 10px;
    row-gap: 30px;
}
.projects-image {
    justify-self: center;
    padding: 4%;
}
@media (max-width: 650px) {
    .projects-grid {
        grid-template-columns: 100%;
    }
}
.links-and-contact {
    display: grid;
    grid-template-columns: 30% 70%;
}
.links {
    justify-self: center;
}
.links-list {
    list-style: none;
    padding: 0;
}
@media (max-width: 650px) {
    .links-and-contact {
        grid-template-columns: 100%;
    }
}
.profile-picture {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  box-shadow: 0 4px 6px 0 rgba(34, 60, 80, .16);
  transition: all ease-in-out .2s;
}
.profile-picture:hover {
    box-shadow: 0 8px 12px rgba(9, 21, 31, 0.16);
}
.project-image {
    border-radius: 5px;
	box-shadow: 0 4px 6px 0 rgba(34, 60, 80, .16);
	transition: all ease-in-out .2s;
}
.project-image:hover {
    filter: brightness(.75);
	box-shadow: 0 8px 12px 0 rgba(34, 60, 80, .16);
}
.project-image-wrapper {
    justify-self: center;
	padding: 4%;
	position: relative;
}
.project-image-wrapper:hover >h4 {
    visibility: visible;
}
.project-image-wrapper >h4 {
    position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	color: rgb(0, 0, 0);
	visibility: hidden;
	z-index: 2;
	transition: all ease-in-out .2s;
}
@media (max-width: 650px) {
	.projects-grid {
		grid-template-columns: 100%;
	}
	.links-and-contact {
		grid-template-columns: 100%;
	}

}
form input, textarea {
	padding: 5px;
	border-radius: 5px;
	width: 240px;
}
form {
	width: 250px;
	margin: 0 auto;
}
form input[type="submit"] {
	width: 250px;
}
.submit-button-wrapper {
	margin: 20px 0;
}
.submit-button-wrapper {
    background-color: #000000;
  }
  .submit-button {
    background-color: #cedeff;
  }
@media (max-width: 480px) {
	.about-grid {
		grid-template-columns: 100%;
	}
}
@media (max-width: 650px) {
	.projects-grid {
		grid-template-columns: 100%;
	}
	.links-and-contact {
		grid-template-columns: 100%;
	}
}

.container > div {
    margin: 20px auto;
  }
hr {
    border: 0;
    height: 1px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0));
  }
