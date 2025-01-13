


const cake = document.getElementById('cake')
const cakeUm = document.getElementById('cakeUm')
const cakeDo = document.getElementById('cakeDo')
const cakeTr = document.getElementById('cakeTr')
const cakeVo = document.getElementById('cakeVo')

function cakeBroken(){
    return cake.src = ('_img/newlogo-pq.jpg') < 3
}

function cakecakeUm(){
    cake.src = '_img/bolo01-pq.jpg'
}

function cakecakeDo(){
    cake.src = '_img/bolo02-pq.jpg'    
}

function cakecakeTr(){
    cake.src = '_img/bolo03-pq.jpg'
}

function cakecakeVo(){
    cake.src = '_img/newlogo-pq.jpg'
}

cakeUm.addEventListener('click', cakecakeUm)
cakeDo.addEventListener('click', cakecakeDo)
cakeTr.addEventListener('click', cakecakeTr)
cakeVo.addEventListener('click', cakecakeVo)
//cake.addEventListener('mouseover', cakecakeVo)
//cake.addEventListener('mouseleave', cakecakeVo)
cake.addEventListener('dblclick', cakecakeVo)

let contador = 1;

setInterval( function(){
    document.getElementById('slide' + contador).checked = true;
    contador++;

    if(counter > 5 ) {
        contador = 1;
    }
}, 4000 );