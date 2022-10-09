# First Solution

document.querySelector('.side-bar .crayons-card .color-base-70').innerHTML = 'I want to become a full stack Javascript developer'

# Second Solution

const titleArray =[]
const titles = document.
querySelectorAll('.as-imagegrid-item .as-imagegrid-item-title')

titles.forEach((title)=>{
titleArray.push(title.firstChild.textContent)})
console.log(titleArray)

# Third Solution

const itemsNodeList = document.querySelector('.article .accordion-homepage')
const newElement = document.createElement("section");

newElement.classList.add("parent")
const h3=document.createElement("h3")
h3.innerText = 'My New FAQ'

itemsNodeList.appendChild(newElement)

newElement.appendChild(h3)

# Fourth Solution

document.querySelector('.contact-us .customer-support .one-tel-number').innerText = "+91 111111111"

# Fifth Solution

document.querySelector(".diwali-deals-product-sale-pro .diwali-deals-product-sale-btn").innerText = "Check out"

# Sixth Solution

const searchBox= document.querySelector('.inner___3Nvdx .right-side-menu___2ykzq .glass-search___X4QNv .searchinput-wrapper___3YrvF .searchinput___19uW0')
searchBox.addEventListener("mouseover", ()=> searchBox.style.backgroundColor= 'Red')

# Seventh Solution

let searchValue = document.querySelector('#top-nav-search-input');
searchValue.value='Hoisting'
let searchSubmit = document.querySelector('#top-nav-search-form')
searchSubmit.submit()

# Eighth Solution

let languagesArray = document.querySelectorAll('#gws-output-pages-elements-homepage_additional_languages\_\_als #SIvCob a')
for(let i=1; i<languagesArray.length; i++){
if(i%2==0){
languagesArray[i].remove()
}
}
console.log(languagesArray)

# Ninth Solution

document.querySelector(".section .container .content-width-extra-large .display-heading-1").style.fontFamily='monospace'

document.querySelector(".section .container .content-width-extra-large .display-heading-1").style.#b1361e

# Tenth Solution

let resultTag = document.querySelector(".btn-cta-big .login-btn-text")
resultTag.addEventListener("mouseover", ()=>resultTag.style.backgroundColor='Red')

# Eleventh Solution

document.querySelector(".header .wrapper .logo .icon").style.backgroundImage='url("https://ineuron.ai/images/ineuron-logo.png")';

# Twelve Solution

document.querySelector('.btn.btn-sm.btn-primary.btn.mb-2').style.backgroundColor='blue'

# Thirteenth Solution

document.querySelector('.fl-col-content .fl-node-5d7c1d1ca1fdd .fl-module-content .fl-heading .fl-heading-text').innerText='JSBOOTCAMP'

# Fourteenth Solution

document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize='80px'

# Fifteenth Solution
let titleArray = document.querySelectorAll("section.ps-top h3.ps-title")
titleArray[4].style.textAlign="right"
# Sixteenth Solution

document.querySelector('.geist-wrapper .jsx-499702677 h4').innerText='Start with Scratch'

# Seventeenth Solution

document.querySelector('.btn-container .retailer_btn-align').innerHTML=new Date()
document.querySelector('.btn-container .retailer_btn-align').style.color='black'
document.querySelector('.btn-container .retailer_btn-align').style.backgroundColor='transparent'

# Eighteenth Solution

document.querySelector('.p-footer').style.backgroundColor = "Orange"

# Nineteenth Solution

document.querySelector(".container .navbar-header a img").src;

# twentieth Solution

document.querySelector('.product-card-content h3').style.color='Orange'
