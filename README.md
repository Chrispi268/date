# date


document.addEventListener("DOMContentLoaded", docReady);
function docReady()
{
    let date = new Date();
    document.getElementById('sorrow1').innerHTML = 
    'с ' + (date.getDate() - 2) + '.0' + (date.getMonth() + 1) + ' по ' + (date.getDate() + 2) 
    + '.0' + (date.getMonth() + 1);
}
document.addEventListener("DOMContentLoaded", simba);
function simba()
{
	let baby = new Date();
document.getElementById('sorrow2').innerHTML = 
    'Только с ' + (baby.getDate() - 2) + '.0' + (baby.getMonth() + 1) + ' по ' + (baby.getDate() + 2) 
    + '.0' + (baby.getMonth() + 1) + ' Скидка 105 BYN на шкаф-купе';
}
document.addEventListener("DOMContentLoaded", sweetcandy);
function sweetcandy()
{
	let lolli = new Date();
document.getElementById('sorrow3').innerHTML = 
    'Только с ' + (lolli.getDate() - 2) + '.0' + (lolli.getMonth() + 1) + ' по ' + (lolli.getDate() + 2) 
    + '.0' + (lolli.getMonth() + 1);
}
