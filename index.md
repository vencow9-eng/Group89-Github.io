---
layout: default
title: "Selamat Datang di Group89!"
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/style.css">

<header class="bg-dark text-white">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-md-3">
                <!-- Logo Section -->
                <a href="{{ site.baseurl }}" class="navbar-brand">
                    <img src="{{ site.baseurl }}/assets/logo.png" alt="Group89" style="height: 50px;">
                </a>
            </div>
            <div class="col-md-9">
                <!-- Navbar links -->
                <nav class="navbar navbar-expand-md">
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav-item">
                                <a class="nav-link" href="{{ site.baseurl }}/about.md">Tentang Kami</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="{{ site.baseurl }}/contact.md">Kontak</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="{{ site.baseurl }}/services.md">Layanan</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="{{ site.baseurl }}/blog.md">Blog</a>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</header>

<main class="container mt-5">
    <!-- Introduction section -->
    <section class="text-center">
        <h2 class="text-gold">Apa yang Bisa Anda Temukan di Group89?</h2>
        <p class="lead">Platform terpercaya untuk mempelajari segala hal tentang esports dan strategi permainan, bersama para profesional.</p>
    </section>

    <!-- Content Cards -->
    <section class="row mt-4">
        <!-- Card 1 -->
        <div class="col-md-4">
            <div class="card bg-dark text-white mb-4">
                <img src="{{ site.baseurl }}/assets/esports.jpg" class="card-img" alt="Panduan Esports">
                <div class="card-img-overlay">
                    <h5 class="card-title">Panduan Esports untuk Pemula</h5>
                    <p class="card-text">Pelajari dasar-dasar esports dan langkah pertama menuju kesuksesan.</p>
                    <a href="{{ site.baseurl }}/guide.md" class="btn btn-warning btn-sm">Baca Selengkapnya</a>
                </div>
            </div>
        </div>
        <!-- Card 2 -->
        <div class="col-md-4">
            <div class="card bg-dark text-white mb-4">
                <img src="{{ site.baseurl }}/assets/tips.jpg" class="card-img" alt="Tips Profesional">
                <div class="card-img-overlay">
                    <h5 class="card-title">Tips dan Trik dari Profesional</h5>
                    <p class="card-text">Dapatkan wawasan langsung dari para ahli di dunia esports.</p>
                    <a href="{{ site.baseurl }}/tips.md" class="btn btn-warning btn-sm">Baca Selengkapnya</a>
                </div>
            </div>
        </div>
        <!-- Card 3 -->
        <div class="col-md-4">
            <div class="card bg-dark text-white mb-4">
                <img src="{{ site.baseurl }}/assets/strategy.jpg" class="card-img" alt="Strategi Game Populer">
                <div class="card-img-overlay">
                    <h5 class="card-title">Strategi untuk Menang dalam Game Populer</h5>
                    <p class="card-text">Pahami teknik dan strategi yang digunakan oleh pemain top.</p>
                    <a href="{{ site.baseurl }}/strategy.md" class="btn btn-warning btn-sm">Baca Selengkapnya</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action (CTA) Section -->
    <section class="cta bg-warning text-center py-5">
        <h3 class="text-dark">Gabung dengan Kami Sekarang</h3>
        <p class="lead text-dark">Bergabunglah dengan komunitas Group89 dan dapatkan tips, trik, dan strategi dari ahli di dunia esports.</p>
        <a href="{{ site.baseurl }}/join.md" class="btn btn-dark btn-lg">Gabung Sekarang</a>
    </section>
</main>

<footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Group89. Dibangun dengan <span style="color:red;">&#9829;</span> menggunakan <a href="https://pages.github.com" target="_blank" class="text-white">GitHub Pages</a>.</p>
    <div>
        <a href="https://twitter.com/Group89" class="text-white mx-2"><i class="fab fa-twitter"></i> Twitter</a>
        <a href="https://www.linkedin.com/company/group89" class="text-white mx-2"><i class="fab fa-linkedin"></i> LinkedIn</a>
        <a href="https://instagram.com/Group89" class="text-white mx-2"><i class="fab fa-instagram"></i> Instagram</a>
    </div>
</footer>
