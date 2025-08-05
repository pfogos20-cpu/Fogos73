# JAVASCRIP - CHANGA

// Formularios simulados

document.getElementById('form-worker').addEventListener('submit', e => {

&nbsp; e.preventDefault();

&nbsp; alert('¡Registro enviado! Te contactaremos pronto.');

&nbsp; e.target.reset();

});



document.getElementById('form-need').addEventListener('submit', e => {

&nbsp; e.preventDefault();

&nbsp; alert('¡Publicación creada! Pronto recibirás presupuestos.');

&nbsp; e.target.reset();

});

