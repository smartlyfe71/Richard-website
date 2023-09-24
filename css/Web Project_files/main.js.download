window.addEventListener('scroll', function() {
    document.querySelector('nav').classList.toggle
    ('window-scroll', window.scrollY > 0)
})



const faqs = document.querySelectorAll('.faq')

faqs.forEach(faq => {
    faq.addEventListener('click', function() {
        faq.classList.toggle('open')

        let icon = faq.querySelector('.faq_icon i');
        if(icon.className === 'bx bx-plus') {
            icon.className = 'bx bx-minus' 

        }

        else{
            icon.className = 'bx bx-plus' 

        }
    })
})



const menu = document.querySelector('.nav_menu');
const menuBtn = document.querySelector('#open-menu-btn');
const closeBtn = document.querySelector('#close-menu-btn');

menuBtn.addEventListener('click', () => {
    menu.style.display = "flex";
    closeBtn.style.display = "inline-block";
    menuBtn.style.display = "none";
});

    
const closenav = () => {
    menu.style.display = "none";
    closeBtn.style.display = "none";
    menuBtn.style.display = "inline-block";
}

closeBtn.addEventListener('click', closenav)

    
