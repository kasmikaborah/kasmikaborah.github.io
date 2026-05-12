---
permalink: /
title: "Kasmika Borah"
author_profile: false
---

<style>

/* ===== GLOBAL ===== */

body{
    margin:0;
    padding:0;
    font-family: "Helvetica Neue", sans-serif;
    background:#f5f5f5;
}

/* ===== NAVBAR ===== */

.custom-navbar{
    width:100%;
    background:#3b1d14;
    padding:20px 60px;
    position:fixed;
    top:0;
    z-index:1000;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:white;
    font-size:40px;
    font-weight:bold;
}

.nav-links a{
    color:white;
    text-decoration:none;
    margin-left:40px;
    font-size:20px;
}

.nav-links a:hover{
    opacity:0.8;
}

/* ===== HERO SECTION ===== */

.hero-section{
    width:100%;
    height:550px;
    background-image:url('{{ site.baseurl }}/images/background.jpg');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:flex-end;
    padding-right:120px;
    margin-top:80px;
    position:relative;
}

.hero-section::before{
    content:'';
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.45);
}

.hero-text{
    position:relative;
    z-index:2;
    color:white;
}

.hero-text h1{
    font-size:80px;
    line-height:1.1;
    margin-bottom:20px;
    font-weight:800;
}

.hero-text h2{
    font-size:38px;
    font-weight:300;
}

/* ===== PROFILE IMAGE ===== */

.profile-section{
    display:flex;
    margin-top:-120px;
    padding-left:120px;
}

.profile-section img{
    width:420px;
    border-radius:5px;
    box-shadow:0px 10px 30px rgba(0,0,0,0.25);
}

/* ===== ABOUT SECTION ===== */

.about-section{
    display:flex;
    padding:70px 120px;
    gap:100px;
    align-items:flex-start;
}

.about-text{
    max-width:800px;
    font-size:24px;
    line-height:1.9;
    color:#333;
}

.about-text h3{
    font-size:40px;
    margin-bottom:20px;
}

/* ===== RESPONSIVE ===== */

@media(max-width:900px){

.hero-section{
    justify-content:center;
    padding:40px;
    text-align:center;
}

.hero-text h1{
    font-size:50px;
}

.hero-text h2{
    font-size:28px;
}

.profile-section{
    justify-content:center;
    padding-left:0;
}

.profile-section img{
    width:280px;
}

.about-section{
    flex-direction:column;
    padding:40px;
}

}

</style>

<!-- ===== NAVBAR ===== -->

<div class="custom-navbar">

    <div class="logo">
        Kasmika Borah, PhD
    </div>

    <div class="nav-links">
        <a href="/">About</a>
        <a href="#">Publications</a>
        <a href="#">Research</a>
        <a href="#">Contact</a>
    </div>

</div>

<!-- ===== HERO SECTION ===== -->

<div class="hero-section">

    <div class="hero-text">

        <h1>
            Kasmika Borah,<br>
            PhD
        </h1>

        <h2>
            Bioinformatics Researcher &<br>
            Computational Biologist
        </h2>

    </div>

</div>

<!-- ===== PROFILE IMAGE ===== -->

<div class="profile-section">

    <img src="/images/profile.jpg">

</div>

<!-- ===== ABOUT SECTION ===== -->

<div class="about-section">

    <div class="about-text">

        <h3>About Me</h3>

        <p>
        I am a bioinformatics researcher and computational biologist with more than 8 years of experience in multi-omics data analysis, cancer genomics, machine learning, deep learning, and computational drug discovery.
        </p>

        <p>
        My research focuses on RNA-seq, single-cell sequencing analysis, biomarker identification, explainable AI, and precision medicine approaches for cancer diagnosis.
        </p>

        <p>
        I have worked in both academic and industry research environments and published multiple peer-reviewed research articles in computational biology and cancer bioinformatics.
        </p>

    </div>

</div>