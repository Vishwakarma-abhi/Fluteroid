const toggleBtn = document.querySelector('.toggle-btn');
const navLinks = document.querySelector('.nav-links');

toggleBtn.addEventListener('click', () => {
  navLinks.classList.toggle('show');
});

window.addEventListener('resize', () => {
  if (window.innerWidth > 768) {
    navLinks.classList.remove('show');
  }
});
