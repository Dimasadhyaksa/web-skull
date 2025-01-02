<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                            aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="10000">
                            <img src="~/assets/img/gerbang.jpg" class="foto d-block w-100" alt="..." height="500">
                            <div class="carousel-caption d-none d-md-block">
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="~/assets/img/tiga.jpg" class="foto d-block w-100" alt="..." height="500">
                            <div class="carousel-caption d-none d-md-block">
                            </div>
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
            <div class="content">
                <div class="card mt-5 mb-5 shadow">
                    <div class="card-header">
                        <h5 class="text-center">Sejarah Singkat SMK Negeri 4 Tasikmalaya</h5>
                    </div>
                    <div class="card-body">
                        <p class="card-text">Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan
                            pada saat itu
                            yakni pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan
                            adanya SMK
                            Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan
                            dari SLTP yang
                            ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di
                            Kecamatan Purbaratu
                            Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa
                            Barat, agar
                            berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
                            Setelah melalui perjuangan yang sangat panjang dari berbagai pihak khususnya Disdik Kota
                            Tasikmalaya dan
                            pihak-pihak terkait lainnya sesuai prosedur dan ketentuan yang berlaku pada waktu itu dengan
                            mengucapkan
                            syukur Alhamdulillah akhirnya pada tahun pelajaran 2010/2011 SMK Negeri 4 Tasikmalaya mulai
                            berdiri, pada
                            awalnya membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta
                            Didik Baru pada
                            waktu itu berjumlah 44 orang. Pada awalnya tempat belajar menumpang di SMP Negeri 17 Kota
                            Tasikmalaya, dan
                            sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya, Untuk Tenaga pendidik dan Tenaga
                            Kependidikan masih
                            dibantu sepenuhnya oleh kedua sekolah tersebut.
                            Pada tahun 2012 keluarlah surat Izin Pendirian berdasarkan keputusan kepala Badan Pelayanan
                            Perizinan
                            Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.</p>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <hr>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.container {
    max-width: 100%;
}

.judul {
    margin-left: 10%;
}

h4,
h5,
p {
    font-family: "Poppins", serif;
    margin-right: auto;
}

.card {
    width: 70%;
    margin: auto;
}

.foto {
    opacity: 0.5;
}

.foto:hover {
    opacity: 1.0;
}
</style>