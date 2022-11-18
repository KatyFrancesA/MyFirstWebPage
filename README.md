# MyFirstWebPage
Created using Career Foundry tutorial 

let submitButton = document.querySelector('#submit-button')

function emailValidate(email) {
    if(email.includes('@')) {
        return true;
    } else {
        return false;
    }
}

function validateNSFW(messageText) {
    if(messageText.includes('fuck', 'Fuck')) {
        return true;
    } else {
        return false;
    }
}

function clickListener(event) {
    event.preventDefault();
    
    let emailInput = document.querySelector('#email');
    let messageInput = document.querySelector('#message');

    let emailText = emailInput.value;
    let messageText = messageInput.value;

    console.log('email:', emailText, 'message:', messageText);
    console.log(emailValidate('abc@xyz.com'))

    if(emailValidate(emailText) !== true) {
        console.log('Invalid email address');
        return false;
    }
    
    if(validateNSFW(messageText) !== true) {
        console.log('Message can\'t contain offensive language');
    }
    return false;

    console.log('Thanks for your message')
}

submitButton.addEventListener('click', clickListener);
