const pages = document.querySelectorAll('.page');
const homeLink = document.getElementById('homeLink');
const aboutLink = document.getElementById('aboutLink');
const backBtn = document.getElementById('backBtn');
const yearEl = document.getElementById('year');

const articles = [
  {
    title: "Geronimo Stilton",
    content: "<p>Simplicity is the ultimate sophistication...</p>"
  },
  {
    title: "Focus in a Distracted World",
    content: "<p>In a world filled with noise, true focus is rare...</p>"
  },
  {
    title: "Designing Without Color",
    content: "<p>Sometimes grayscale can speak louder than colors...</p>"
  }
]

if (yearEl) {
  yearEl.textContent = new Date().getFullYear();
}

const form = document.querySelector('form');


form.addEventListener('submit', handleSubmit);

function handleSubmit(event) {
  
  event.preventDefault();

  
  const username = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;

 
  console.log('Form Submitted!');
  console.log('Username:', username);
  console.log('Email:', email);
  console.log('Message:', message);


function showPage(id) {
  pages.forEach(page => {
    page.style.visibility = 'hidden';
  });
  document.getElementById(id).style.visibility = 'visible';
  document.addEventListener('DOMContentLoaded', () => {
  const searchInput = document.getElementById('searchInput');
  const itemsList = document.getElementById('itemsList');
  const listItems = itemsList.getElementsByTagName('li');

  searchInput.addEventListener('keyup', () => {
    const filter = searchInput.value.toLowerCase();

    for (let i = 0; i < listItems.length; i++) {
      const textValue = listItems[i].textContent || listItems[i].innerText;
      if (textValue.toLowerCase().indexOf(filter) > -1) {
        listItems[i].style.display = '';
      } else {
        listItems[i].style.display = 'none';
      }
    }
  });
});
}

homeLink.onclick = () => showPage('homePage');
aboutLink.onclick = () => showPage('aboutPage');
backBtn.onclick = () => showPage('homePage');

function openArticle(id) {
  const article = articles[i];
  const content = document.getElementById('articleContent');
  content.innerHTML = `<h2>${article.title}</h2>${article.content}`;
  showPage('articlePage');
}
