/*==========================================================
  MICROSOFT 365 ADMINISTRATION LEARNING PORTFOLIO
  STYLE.CSS

  PART 1 — FOUNDATION
  Google Font • Reset • Variables • Base Styles
  Container • Sections
==========================================================*/


/*==========================================================
  GOOGLE FONT
==========================================================*/

@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap");


/*==========================================================
  THEME VARIABLES
==========================================================*/

:root{

    /* Microsoft Blue */

    --primary:#2563eb;
    --primary-dark:#1d4ed8;
    --secondary:#60a5fa;


    /* Background */

    --background:#f5f7fb;
    --surface:#ffffff;


    /* Text */

    --text:#1f2937;
    --text-light:#6b7280;
    --text-white:#ffffff;


    /* Borders */

    --border:#e5e7eb;


    /* Status */

    --success:#22c55e;
    --warning:#f59e0b;
    --danger:#ef4444;


    /* Radius */

    --radius-sm:8px;
    --radius:16px;
    --radius-lg:24px;


    /* Shadows */

    --shadow-sm:
    0 5px 15px rgba(0,0,0,.05);


    --shadow:
    0 10px 30px rgba(0,0,0,.08);


    --shadow-lg:
    0 20px 45px rgba(0,0,0,.12);


    /* Animation */

    --transition:.35s ease;


    /* Layout */

    --container-width:1200px;

}



/*==========================================================
  CSS RESET
==========================================================*/

*,
*::before,
*::after{

    margin:0;

    padding:0;

    box-sizing:border-box;

}



html{

    scroll-behavior:smooth;

}



body{

    font-family:"Inter",sans-serif;

    background:var(--background);

    color:var(--text);

    line-height:1.7;

    overflow-x:hidden;

    -webkit-font-smoothing:antialiased;

    text-rendering:optimizeLegibility;

}



/*==========================================================
  GLOBAL ELEMENTS
==========================================================*/


img{

    display:block;

    max-width:100%;

    height:auto;

}



a{

    color:inherit;

    text-decoration:none;

}



ul,
ol{

    list-style:none;

}



button,
input,
textarea,
select{

    font:inherit;

}



button{

    cursor:pointer;

    border:none;

    background:none;

}



/*==========================================================
  CONTAINER
==========================================================*/


.container{

    width:min(90%,var(--container-width));

    margin-inline:auto;

}



/*==========================================================
  SECTION
==========================================================*/


section{

    padding:90px 0;

    position:relative;

}



/*==========================================================
  SECTION TITLE
==========================================================*/


.section-title{

    text-align:center;

    max-width:760px;

    margin:0 auto 60px;

}



.section-title h2{

    font-size:clamp(2rem,4vw,2.75rem);

    font-weight:800;

    color:var(--text);

    margin-bottom:15px;

    letter-spacing:-.5px;

}



.section-title p{

    color:var(--text-light);

    font-size:1.05rem;

    line-height:1.8;

}



/*==========================================================
  BACKGROUND UTILITIES
==========================================================*/


.bg-white{

    background:var(--surface);

}



.bg-light{

    background:var(--background);

}



.bg-primary{

    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );

    color:var(--text-white);

}



/*==========================================================
  REUSABLE CARD
==========================================================*/


.card{

    position:relative;

    background:var(--surface);

    border:1px solid var(--border);

    border-radius:var(--radius);

    box-shadow:var(--shadow);

    transition:var(--transition);

    overflow:hidden;

}



.card:hover{

    transform:translateY(-8px);

    box-shadow:var(--shadow-lg);

}



/*==========================================================
  TEXT SELECTION
==========================================================*/


::selection{

    background:var(--primary);

    color:#fff;

}



/*==========================================================
  SCROLLBAR
==========================================================*/


::-webkit-scrollbar{

    width:10px;

}



::-webkit-scrollbar-track{

    background:#edf2f7;

}



::-webkit-scrollbar-thumb{

    background:var(--primary);

    border-radius:50px;

}



::-webkit-scrollbar-thumb:hover{

    background:var(--primary-dark);

}

/*==========================================================
  PART 2 — HEADER & NAVIGATION

  Header • Navbar • Logo • Navigation
  Dropdown • Mobile Menu
==========================================================*/


/*==========================================================
  HEADER
==========================================================*/


header{

    position:fixed;

    inset:0 0 auto 0;

    width:100%;

    background:rgba(255,255,255,.92);

    backdrop-filter:blur(14px);

    -webkit-backdrop-filter:blur(14px);

    border-bottom:1px solid rgba(229,231,235,.8);

    transition:var(--transition);

    z-index:1000;

}



header.scrolled{

    background:rgba(255,255,255,.98);

    box-shadow:var(--shadow);

}



/*==========================================================
  NAVBAR
==========================================================*/


.navbar{

    width:min(90%,1200px);

    height:80px;

    margin:auto;

    display:flex;

    align-items:center;

    justify-content:space-between;

}



/*==========================================================
  LOGO
==========================================================*/


.logo{

    display:flex;

    align-items:center;

    gap:12px;

    font-size:1.4rem;

    font-weight:800;

    color:var(--primary);

    white-space:nowrap;

}



.logo i{

    font-size:2rem;

}



/*==========================================================
  DESKTOP NAVIGATION
==========================================================*/


.nav-links{

    display:flex;

    align-items:center;

    gap:35px;

}



.nav-links > li{

    position:relative;

}



.nav-links a{

    position:relative;

    display:flex;

    align-items:center;

    gap:8px;

    font-weight:600;

    color:var(--text);

    transition:var(--transition);

}



.nav-links a:hover{

    color:var(--primary);

}



/* underline */


.nav-links > li > a::after{

    content:"";

    position:absolute;

    left:0;

    bottom:-8px;

    width:0;

    height:3px;

    background:var(--primary);

    border-radius:50px;

    transition:var(--transition);

}



.nav-links > li > a:hover::after{

    width:100%;

}



/*==========================================================
  MENU BUTTON
==========================================================*/


.menu-btn{

    display:none;

    font-size:1.8rem;

    color:var(--primary);

    cursor:pointer;

    transition:var(--transition);

}



.menu-btn:hover{

    transform:rotate(90deg);

}



/*==========================================================
  DROPDOWN
==========================================================*/


.dropdown{

    position:relative;

}



.dropdown > a{

    display:flex;

    align-items:center;

    gap:8px;

}



.dropdown > a i{

    font-size:12px;

    transition:.3s;

}



/* Dropdown container */


.dropdown-menu{

    position:absolute;

    top:60px;

    left:50%;

    transform:

    translateX(-50%)

    translateY(15px);


    width:300px;

    padding:12px 0;

    background:#fff;

    border-radius:14px;

    border:1px solid rgba(0,0,0,.05);

    box-shadow:0 20px 40px rgba(0,0,0,.15);

    opacity:0;

    visibility:hidden;

    pointer-events:none;

    transition:.3s;

}



/* open dropdown */


.dropdown.active > a i{

    transform:rotate(180deg);

}



.dropdown.active .dropdown-menu{

    opacity:1;

    visibility:visible;

    pointer-events:auto;

    transform:

    translateX(-50%)

    translateY(0);

}



/* dropdown links */


.dropdown-menu li{

    width:100%;

}



.dropdown-menu a{

    display:block;

    padding:14px 22px;

    text-align:center;

    font-weight:500;

}



.dropdown-menu a::after{

    display:none;

}



.dropdown-menu a:hover{

    background:var(--primary);

    color:#fff;

}



/* force close from JS */


.dropdown.hide-dropdown .dropdown-menu{

    opacity:0 !important;

    visibility:hidden !important;

    pointer-events:none !important;

    transform:

    translateX(-50%)

    translateY(15px);

}



/*==========================================================
  TABLET
==========================================================*/


@media(max-width:992px){

    .navbar{

        height:75px;

    }

}



/*==========================================================
  MOBILE NAVIGATION
==========================================================*/


@media(max-width:768px){


    header{

        z-index:1100;

    }



    .navbar{

        height:75px;
        justify-content:flex-start;

        gap:20px;

    }



    .menu-btn{

        display:block;

        order:1;

    }



    .logo{

        order:2;

    }



    .nav-links{

        position:absolute;

        top:75px;

        left:0;

        width:100%;


        background:#fff;


        display:flex;

        flex-direction:column;

        align-items:flex-start;


        gap:0;


        padding:20px 0;


        box-shadow:

        0 15px 35px rgba(0,0,0,.08);



        transform:translateX(-100%);

        transition:.35s ease;

    }



    .nav-links.active{

        transform:translateX(0);

    }




    .nav-links > li{

        width:100%;

    }



    .nav-links > li > a{

        width:100%;

        padding:16px 30px;

        justify-content:flex-start;

    }



    .nav-links > li > a::after{

        display:none;

    }

}


/*==========================================================
  MOBILE DROPDOWN FIX
==========================================================*/

@media(max-width:768px){


    .dropdown{

        width:100%;

    }


    .dropdown > a{

        width:100%;

        justify-content:space-between;

        padding:16px 30px;

    }



    .dropdown-menu{

        position:static !important;

        left:auto !important;

        top:auto !important;

        width:100% !important;

        margin:0;

        padding:0;

        display:none;

        background:#f8fafc;

        border:none;

        box-shadow:none;

        opacity:1;

        visibility:visible;

        pointer-events:auto;

        transform:none !important;

    }



    .dropdown.active .dropdown-menu{

        display:block;

        transform:none !important;

    }



    .dropdown-menu a{

        padding:14px 55px;

        text-align:left;

        color:#1f2937;

        display:block;

    }



    .dropdown-menu a:hover{

        background:#eff6ff;

        color:var(--primary);

    }


}

/*==========================================================
  PART 3 — HERO SECTION

  Hero • Badge • Buttons
  Profile Card • Animations
==========================================================*/


/*==========================================================
  HERO
==========================================================*/


.hero{

    position:relative;

    min-height:100vh;

    display:flex;

    align-items:center;

    padding:120px 0 80px;


    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    color:#fff;

    overflow:hidden;

}



/* decorative glow */


.hero::before{

    content:"";

    position:absolute;

    width:520px;

    height:520px;

    top:-180px;

    right:-180px;


    border-radius:50%;


    background:rgba(255,255,255,.08);


    filter:blur(90px);

}



.hero::after{

    content:"";

    position:absolute;

    width:380px;

    height:380px;


    left:-120px;

    bottom:-120px;


    border-radius:50%;


    background:rgba(255,255,255,.05);


    filter:blur(70px);

}



/*==========================================================
  HERO LAYOUT
==========================================================*/


.hero-wrapper{

    display:grid;

    grid-template-columns:1.15fr .85fr;

    align-items:center;

    gap:70px;

    position:relative;

    z-index:2;

}



/*==========================================================
  HERO CONTENT
==========================================================*/


.hero-content{

    animation:slideLeft .9s ease both;

}



.badge{

    display:inline-flex;

    align-items:center;

    justify-content:center;


    padding:10px 18px;


    margin-bottom:25px;


    background:rgba(255,255,255,.12);


    border:1px solid rgba(255,255,255,.18);


    border-radius:8px;


    font-size:.95rem;


    font-weight:600;


    color:#fff;


    letter-spacing:.3px;

}



/* heading */


.hero h1{

    font-size:clamp(2.8rem,6vw,4.4rem);


    font-weight:800;


    line-height:1.1;


    letter-spacing:-2px;


    margin-bottom:25px;

}



.hero h1 span{

    display:block;


    background:linear-gradient(
        90deg,
        #ffffff,
        #bfdbfe
    );


    -webkit-background-clip:text;

    background-clip:text;


    -webkit-text-fill-color:transparent;

}



/* paragraph */


.hero p{

    max-width:620px;


    margin-bottom:40px;


    font-size:1.08rem;


    line-height:1.9;


    color:rgba(255,255,255,.88);

}



/*==========================================================
  BUTTONS
==========================================================*/


.hero-buttons{

    display:flex;

    flex-wrap:wrap;

    gap:18px;

}



.btn{

    display:inline-flex;

    align-items:center;

    justify-content:center;


    gap:10px;


    min-width:180px;


    padding:15px 32px;


    border-radius:10px;


    font-weight:700;


    transition:var(--transition);

}



/* Primary button */


.btn-primary{

    background:#fff;

    color:var(--primary);

}



.btn-primary:hover{

    transform:translateY(-5px);

    box-shadow:

    0 12px 30px rgba(0,0,0,.15);

}



/* Secondary button */


.btn-secondary{

    background:transparent;


    color:#fff;


    border:2px solid rgba(255,255,255,.4);

}



.btn-secondary:hover{

    background:#fff;

    color:var(--primary);

}



/*==========================================================
  PROFILE IMAGE AREA
==========================================================*/


.hero-image{

    display:flex;

    justify-content:center;


    animation:slideRight .9s ease both;

}



/*==========================================================
  PROFILE CARD
==========================================================*/


.profile-card{

    width:360px;


    padding:14px;


    border-radius:20px;


    background:linear-gradient(
        135deg,
        rgba(255,255,255,.18),
        rgba(255,255,255,.05)
    );


    border:1px solid rgba(255,255,255,.25);


    box-shadow:

    0 20px 45px rgba(0,0,0,.25);


    transition:var(--transition);

}



.profile-card:hover{

    transform:translateY(-10px);

}



/*==========================================================
  PROFILE IMAGE
==========================================================*/


.profile-image{

    width:100%;


    height:420px;


    object-fit:cover;


    border-radius:12px;


    /* prevent blur */

    filter:none;

}



/*==========================================================
  PROFILE INFORMATION
==========================================================*/


.profile-info{

    margin-top:15px;


    padding:18px 20px;


    background:rgba(255,255,255,.12);


    border:1px solid rgba(255,255,255,.25);


    border-radius:14px;


    text-align:center;

}



.profile-info h3{

    color:#fff;


    font-size:1.35rem;


    font-weight:800;


    margin-bottom:6px;

}



.profile-info p{

    color:rgba(255,255,255,.9);


    font-size:.9rem;


    font-weight:500;


    line-height:1.5;


    margin:0;

}



/*==========================================================
  ANIMATIONS
==========================================================*/


@keyframes slideLeft{


    from{

        opacity:0;

        transform:translateX(-40px);

    }


    to{

        opacity:1;

        transform:translateX(0);

    }

}



@keyframes slideRight{


    from{

        opacity:0;

        transform:translateX(40px);

    }


    to{

        opacity:1;

        transform:translateX(0);

    }

}



/*==========================================================
  RESPONSIVE
==========================================================*/


@media(max-width:992px){


    .hero{

        padding:140px 0 80px;

    }



    .hero-wrapper{

        grid-template-columns:1fr;

        gap:50px;

        text-align:center;

    }



    .hero-content{

        order:2;

    }



    .hero-image{

        order:1;

    }



    .hero p{

        margin-inline:auto;

    }



    .hero-buttons{

        justify-content:center;

    }


}



@media(max-width:768px){


    .hero{

        padding:120px 0 70px;

    }



    .hero-buttons{

        flex-direction:column;

        align-items:center;

    }



    .btn{

        width:260px;

    }



    .profile-card{

        width:280px;

    }



    .profile-image{

        height:330px;

    }


}



@media(max-width:576px){


    .profile-card{

        width:250px;

    }



    .profile-image{

        height:300px;

    }


}

/*==========================================================
  PART 4 — ABOUT + CARD SYSTEM

  About Section
  Learning Journey
  Organization Settings
  Shared Mailboxes
  License Management
==========================================================*/


/*==========================================================
  ABOUT SECTION
==========================================================*/


#about{

    background:var(--surface);

}



/*==========================================================
  ABOUT GRID
==========================================================*/


.about-grid{

    display:grid;

    grid-template-columns:
    repeat(auto-fit,minmax(300px,1fr));


    gap:30px;

}



/*==========================================================
  ABOUT CARD
==========================================================*/


.about-card{

    padding:40px 35px;


    text-align:center;


    background:var(--surface);


    border:1px solid var(--border);


    border-radius:var(--radius);


    box-shadow:var(--shadow);


    transition:var(--transition);


}



/* hover */


.about-card:hover{

    transform:translateY(-10px);


    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    border-color:transparent;


    box-shadow:var(--shadow-lg);

}



/* icon */


.about-card i{

    font-size:3rem;


    color:var(--primary);


    margin-bottom:25px;


    transition:var(--transition);

}



.about-card:hover i{

    color:#fff;


    transform:

    scale(1.1)

    rotate(-5deg);

}



/* title */


.about-card h3{

    font-size:1.45rem;


    font-weight:700;


    margin-bottom:15px;


    color:var(--text);


    transition:var(--transition);

}



/* text */


.about-card p{

    color:var(--text-light);


    line-height:1.8;


    transition:var(--transition);

}



.about-card:hover h3,
.about-card:hover p{

    color:#fff;

}



/*==========================================================
  SHARED CARD SECTIONS
==========================================================*/


#journey,
#organization-settings,
#shared-mailboxes,
#license-management{

    background:var(--surface);

}



/*==========================================================
  CARD GRID
==========================================================*/


.cards{

    display:grid;


    grid-template-columns:
    repeat(auto-fit,minmax(320px,1fr));


    gap:30px;

}



/*==========================================================
  MAIN CARD SYSTEM
==========================================================*/


.card{

    position:relative;


    padding:35px;


    background:var(--surface);


    border:1px solid var(--border);


    border-radius:var(--radius);


    box-shadow:var(--shadow);


    overflow:hidden;


    transition:var(--transition);

}



.card:hover{

    transform:translateY(-10px);


    box-shadow:var(--shadow-lg);

}



/* top accent */


.card::before{

    content:"";


    position:absolute;


    top:0;

    left:0;


    width:100%;


    height:5px;


    background:linear-gradient(
        90deg,
        var(--primary),
        var(--secondary)
    );

}



/*==========================================================
  CARD ICON
==========================================================*/


.card i{

    font-size:3rem;


    color:var(--primary);


    margin-bottom:22px;


    transition:var(--transition);

}



.card:hover i{

    transform:scale(1.08);

}



/*==========================================================
  CARD TEXT
==========================================================*/


.card h3{

    font-size:1.45rem;


    font-weight:700;


    margin-bottom:15px;

}



.card p{

    color:var(--text-light);


    line-height:1.8;


    margin-bottom:22px;

}



/*==========================================================
  STEP NUMBER
==========================================================*/


.number{

    position:absolute;


    top:25px;


    right:25px;


    width:48px;


    height:48px;


    display:flex;


    justify-content:center;


    align-items:center;


    border-radius:50%;


    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    color:#fff;


    font-weight:700;


    font-size:.95rem;

}



/*==========================================================
  LEARN MORE
==========================================================*/


.learn-more{

    display:inline-flex;


    align-items:center;


    gap:8px;


    color:var(--primary);


    font-weight:700;


    transition:var(--transition);

}



.learn-more::after{

    content:"→";


    transition:var(--transition);

}



.learn-more:hover{

    color:var(--primary-dark);

}



.learn-more:hover::after{

    transform:translateX(6px);

}



/*==========================================================
  PROGRESS CARD
==========================================================*/


.progress-card{

    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    color:#fff;

}



.progress-card::before{

    display:none;

}



.progress-card i,
.progress-card h3{

    color:#fff;

}



.progress-card p{

    color:rgba(255,255,255,.9);

}



/*==========================================================
  PROGRESS LIST
==========================================================*/


.progress-list{

    margin-top:25px;

}



.progress-list li{

    display:flex;


    align-items:center;


    gap:12px;


    margin-bottom:16px;


    font-weight:600;

}



.progress-list i{

    font-size:1rem;


    color:#22c55e;


    margin:0;

}



/*==========================================================
  RESPONSIVE
==========================================================*/


@media(max-width:768px){


    .about-grid,
    .cards{

        grid-template-columns:1fr;

    }



    .about-card,
    .card{

        padding:30px;

    }


}



@media(max-width:576px){


    .about-card,
    .card{

        padding:26px;

    }


}

/*==========================================================
  PART 5 — STATISTICS • ROADMAP • PROJECTS • GOALS

  Stats
  Timeline
  Projects
  Learning Goals
==========================================================*/


/*==========================================================
  STATISTICS
==========================================================*/


.stats{

    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    color:#fff;

}



.stats .container{

    display:grid;


    grid-template-columns:
    repeat(auto-fit,minmax(220px,1fr));


    gap:30px;

}



.stat{

    text-align:center;


    padding:35px 20px;

}



.stat h2{

    font-size:clamp(2.5rem,5vw,3.5rem);


    font-weight:800;


    margin-bottom:10px;

}



.stat p{

    font-size:1rem;


    opacity:.9;

}



/*==========================================================
  ROADMAP
==========================================================*/


#roadmap{

    background:var(--surface);

}



.timeline{

    display:grid;


    grid-template-columns:
    repeat(auto-fit,minmax(320px,1fr));


    gap:30px;

}



.timeline-item{

    position:relative;


    padding:35px;


    background:var(--surface);


    border:1px solid var(--border);


    border-radius:var(--radius);


    box-shadow:var(--shadow);


    overflow:hidden;


    transition:var(--transition);

}



.timeline-item::before{

    content:"";


    position:absolute;


    top:0;


    left:0;


    width:100%;


    height:5px;


    background:linear-gradient(
        90deg,
        var(--primary),
        var(--secondary)
    );

}



.timeline-item:hover{

    transform:translateY(-10px);


    box-shadow:var(--shadow-lg);

}



.timeline-item h3{

    color:var(--primary);


    font-size:1.35rem;


    margin-bottom:15px;

}



.timeline-item p{

    color:var(--text-light);


    line-height:1.8;

}



/*==========================================================
  PROJECTS
==========================================================*/


#projects{

    background:var(--background);

}



#projects .cards{

    display:grid;


    grid-template-columns:
    repeat(auto-fit,minmax(320px,1fr));


    gap:30px;

}



#projects .card{

    text-align:center;

}



/* project images */


#projects .card img,
.card img{

    width:100%;


    height:auto;


    object-fit:cover;


    margin:20px 0;


    border-radius:12px;


    cursor:pointer;


    transition:transform .35s ease;

}



#projects .card:hover img,
.card:hover img{

    transform:scale(1.03);

}



/*==========================================================
  GOALS
==========================================================*/


#goals{

    background:var(--surface);

}



#goals .cards{

    display:grid;


    grid-template-columns:
    repeat(auto-fit,minmax(300px,1fr));


    gap:30px;

}



#goals .card{

    text-align:center;

}



#goals .card:hover{

    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    border-color:transparent;

}



#goals .card:hover h3,
#goals .card:hover p,
#goals .card:hover i{

    color:#fff;

}



/*==========================================================
  RESPONSIVE
==========================================================*/


@media(max-width:768px){


    .timeline{

        grid-template-columns:1fr;

    }


}

/*==========================================================
  PART 6 — CONTACT • FOOTER • BACK TO TOP

  Contact Section
  Form
  Footer
  Scroll Button
==========================================================*/


/*==========================================================
  CONTACT SECTION
==========================================================*/


#contact{

    background:linear-gradient(
        135deg,
        var(--primary),
        var(--primary-dark)
    );


    color:#fff;

}



/*==========================================================
  CONTACT WRAPPER
==========================================================*/


.contact-wrapper{

    width:min(90%,1200px);


    margin:auto;


    display:grid;


    grid-template-columns:1fr 430px;


    gap:60px;


    align-items:center;

}



/*==========================================================
  CONTACT INFORMATION
==========================================================*/


.contact-info h2{

    font-size:clamp(2.2rem,5vw,3rem);


    font-weight:800;


    margin-bottom:20px;

}



.contact-info p{

    color:rgba(255,255,255,.9);


    line-height:1.9;


    margin-bottom:18px;

}



.contact-info strong{

    color:#fff;

}



/*==========================================================
  CONTACT BUTTONS
==========================================================*/


.contact-buttons{

    display:flex;


    flex-wrap:wrap;


    gap:16px;


    margin-top:35px;

}



.btn-contact{

    display:inline-flex;


    align-items:center;


    justify-content:center;


    gap:10px;


    min-width:180px;


    padding:14px 28px;


    border-radius:10px;


    font-weight:700;


    transition:var(--transition);

}



/* LinkedIn button */


.btn-contact.btn-primary{

    background:#fff;


    color:var(--primary);

}



.btn-contact.btn-primary:hover{

    transform:translateY(-4px);


    box-shadow:

    0 12px 30px rgba(0,0,0,.15);

}



/* Outline button */


.btn-outline{

    background:transparent;


    color:#fff;


    border:2px solid rgba(255,255,255,.4);

}



.btn-outline:hover{

    background:#fff;


    color:var(--primary);

}



/*==========================================================
  CONTACT FORM CARD
==========================================================*/


.contact-form-card{

    background:#fff;


    border-radius:20px;


    padding:35px;


    box-shadow:var(--shadow-lg);

}



.contact-form-card h3{

    display:flex;


    align-items:center;


    gap:10px;


    color:var(--primary);


    font-size:1.5rem;


    margin-bottom:25px;

}



/*==========================================================
  FORM ELEMENTS
==========================================================*/


.contact-form-card input,
.contact-form-card textarea{

    width:100%;


    padding:15px 18px;


    margin-bottom:18px;


    border:1px solid var(--border);


    border-radius:10px;


    background:#fff;


    color:var(--text);


    transition:var(--transition);

}



.contact-form-card input:focus,
.contact-form-card textarea:focus{

    outline:none;


    border-color:var(--primary);


    box-shadow:

    0 0 0 4px rgba(37,99,235,.12);

}



.contact-form-card textarea{

    min-height:150px;


    resize:none;

}



/*==========================================================
  FORM BUTTON
==========================================================*/


.contact-form-card button{

    width:100%;


    padding:15px;


    border-radius:10px;


    background:var(--primary);


    color:#fff;


    font-weight:700;


    transition:var(--transition);

}



.contact-form-card button:hover{

    background:var(--primary-dark);


    transform:translateY(-3px);

}



/*==========================================================
  FOOTER
==========================================================*/


footer{

    background:#111827;


    color:#d1d5db;


    text-align:center;


    padding:35px 20px;

}



footer p{

    margin:8px 0;

}



footer a{

    color:#fff;


    font-weight:600;


    transition:var(--transition);

}



footer a:hover{

    color:var(--secondary);

}



/*==========================================================
  BACK TO TOP BUTTON
==========================================================*/


#topBtn{

    position:fixed;


    right:30px;


    bottom:30px;


    width:55px;


    height:55px;


    display:none;


    align-items:center;


    justify-content:center;


    border-radius:50%;


    background:var(--primary);


    color:#fff;


    box-shadow:var(--shadow);


    transition:var(--transition);


    z-index:999;

}



#topBtn:hover{

    background:var(--primary-dark);


    transform:translateY(-5px);

}



/*==========================================================
  RESPONSIVE
==========================================================*/


@media(max-width:992px){


    .contact-wrapper{

        grid-template-columns:1fr;

    }



    .contact-info{

        text-align:center;

    }



    .contact-buttons{

        justify-content:center;

    }



    .contact-form-card{

        width:100%;


        max-width:650px;


        margin:auto;

    }


}



@media(max-width:576px){


    .contact-buttons{

        flex-direction:column;


        align-items:center;

    }



    .btn-contact{

        width:100%;


        max-width:260px;

    }



    .contact-form-card{

        padding:25px;

    }


}
