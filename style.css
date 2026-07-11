/* ==========================================================
   MICROSOFT 365 ADMINISTRATION LEARNING PORTFOLIO
   script.js
========================================================== */

document.addEventListener("DOMContentLoaded", () => {

    /* ==========================================
       ELEMENTS
    ========================================== */

    const header = document.querySelector("header");
    const menuBtn = document.querySelector(".menu-btn");
    const navLinks = document.querySelector(".nav-links");
    const topBtn = document.getElementById("topBtn");
    const dropdowns = document.querySelectorAll(".dropdown");

    /* ==========================================
       MOBILE MENU
    ========================================== */

    if (menuBtn) {

        menuBtn.addEventListener("click", () => {

            navLinks.classList.toggle("active");

            menuBtn.innerHTML = navLinks.classList.contains("active")
                ? '<i class="fas fa-times"></i>'
                : '<i class="fas fa-bars"></i>';

        });

    }


    

    /* ==========================================
       MOBILE DROPDOWN
    ========================================== */

  dropdowns.forEach(dropdown => {

    const trigger = dropdown.querySelector(".dropdown-toggle");

    trigger.addEventListener("click", function (e) {

    e.preventDefault();

    dropdowns.forEach(item => {

        if (item !== dropdown) {
            item.classList.remove("active");
        }

    });

    dropdown.classList.toggle("active");

 });

});



document.addEventListener("click", function (e) {

    dropdowns.forEach(dropdown => {

        if (!dropdown.contains(e.target)) {

            dropdown.classList.remove("active");

        }

    });

});


document.querySelectorAll(".dropdown-menu a").forEach(link => {

    link.addEventListener("click", () => {

        dropdowns.forEach(dropdown => {

            dropdown.classList.remove("active");

        });

    });

});


/* ==========================================
   DESKTOP DROPDOWN CLOSE AFTER CLICK
========================================== */

document.querySelectorAll(".dropdown-menu a").forEach(link => {

    link.addEventListener("click", () => {

        if (window.innerWidth > 768) {

            const dropdown = link.closest(".dropdown");

            // Temporarily disable hover
            dropdown.classList.add("hide-dropdown");

            // Re-enable after navigation starts
            setTimeout(() => {
                dropdown.classList.remove("hide-dropdown");
            }, 300);

        }

    });

});

    /* ==========================================
       CLOSE MENU AFTER CLICKING A LINK
    ========================================== */

    document.querySelectorAll(".nav-links a").forEach(link => {

        link.addEventListener("click", function () {

            if (this.parentElement.classList.contains("dropdown")) return;

            navLinks.classList.remove("active");

            if (menuBtn) {

                menuBtn.innerHTML = '<i class="fas fa-bars"></i>';

            }

        });

    });

    /* ==========================================
       STICKY HEADER
    ========================================== */

    window.addEventListener("scroll", () => {

        header.classList.toggle("scrolled", window.scrollY > 40);

    });

    /* ==========================================
       BACK TO TOP BUTTON
    ========================================== */

    if (topBtn) {

        window.addEventListener("scroll", () => {

            topBtn.style.display =
                window.scrollY > 500 ? "flex" : "none";

        });

        topBtn.addEventListener("click", () => {

            window.scrollTo({

                top: 0,

                behavior: "smooth"

            });

        });

    }

    /* ==========================================
       SMOOTH SCROLL
    ========================================== */

    document.querySelectorAll('a[href^="#"]').forEach(anchor => {

        anchor.addEventListener("click", function (e) {

            const id = this.getAttribute("href");

            if (id === "#") return;

            const target = document.querySelector(id);

            if (!target) return;

            e.preventDefault();

            window.scrollTo({

                top: target.offsetTop - 70,

                behavior: "smooth"

            });

        });

    });

    /* ==========================================
       ACTIVE NAVIGATION
    ========================================== */

    const sections = document.querySelectorAll("section");
    const navItems = document.querySelectorAll(".nav-links a");

    function updateActiveNav() {

        let current = "";

        sections.forEach(section => {

            const top = section.offsetTop - 120;

            if (window.scrollY >= top) {

                current = section.id;

            }

        });

        navItems.forEach(link => {

            link.classList.remove("active");

            if (link.getAttribute("href") === "#" + current) {

                link.classList.add("active");

            }

        });

    }

    window.addEventListener("scroll", updateActiveNav);

    updateActiveNav();

    /* ==========================================
       SCROLL REVEAL
    ========================================== */

    const revealItems = document.querySelectorAll(

        ".card, .about-card, .timeline-item, .stat"

    );

    const revealObserver = new IntersectionObserver(entries => {

        entries.forEach(entry => {

            if (entry.isIntersecting) {

                entry.target.classList.add("show");

            }

        });

    }, {

        threshold: .15

    });

    revealItems.forEach(item => {

        item.classList.add("hidden");

        revealObserver.observe(item);

    });

    /* ==========================================
       COUNTER ANIMATION
    ========================================== */

    const counters = document.querySelectorAll(".stat h2");

    function animateCounter(counter) {

        const target = parseInt(counter.dataset.target || counter.innerText);

        if (isNaN(target)) return;

        let value = 0;

        const increment = Math.ceil(target / 50);

        function update() {

            value += increment;

            if (value >= target) {

                counter.innerText = target + "+";

            } else {

                counter.innerText = value;

                requestAnimationFrame(update);

            }

        }

        update();

    }

    const counterObserver = new IntersectionObserver(entries => {

        entries.forEach(entry => {

            if (entry.isIntersecting) {

                animateCounter(entry.target);

                counterObserver.unobserve(entry.target);

            }

        });

    });

    counters.forEach(counter => {

        counterObserver.observe(counter);

    });

    /* ==========================================
       FOOTER YEAR
    ========================================== */

    const year = document.querySelector(".current-year");

    if (year) {

        year.textContent = new Date().getFullYear();

    }

    /* ==========================================
       CONSOLE
    ========================================== */

    console.clear();

    console.log(

        "%cMicrosoft 365 Administration Learning Portfolio",

        "color:#0078D4;font-size:20px;font-weight:bold"

    );

    console.log(

        "%cWebsite Loaded Successfully ✔",

        "color:#22c55e;font-size:14px"

    );

});



/*=========================================
IMAGE MODAL
=========================================*/

const modal = document.getElementById("imageModal");
const modalImg = document.getElementById("modalImage");
const closeModal = document.querySelector(".close-image");

document.querySelectorAll(".clickable-image").forEach(image => {

    image.addEventListener("click", () => {

        modal.style.display = "flex";
        modalImg.src = image.src;
        modalImg.alt = image.alt;

    });

});

closeModal.addEventListener("click", () => {

    modal.style.display = "none";

});

modal.addEventListener("click", function(e){

    if(e.target === modal){

        modal.style.display = "none";

    }

});
