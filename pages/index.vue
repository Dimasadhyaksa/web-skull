<script setup>
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="layer">
                <img src="~/assets/img/pembuka.jpg" alt="" width="100%">
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row pt-5">
            <div class="jumbotron text-center">
                <img src="/assets/img/kepsek.png" alt="dimas" width="200px" class="rounded-circle img-thumbnail" />
                <h1 class="name">Kurniawan S.Pd, M.Pd</h1>

                <h4 class="kepsek pt-4">Kepala SMK Negeri 4 Tasikmalaya</h4>
                <p class="lead">terwujudnya lulusan yang cerdas, kompetitif, adaptif, produktif, dan ber imtak</p>
            </div>
        </div>
    </div>

    <div class="background mt-5">
        <div class="container">
            <h1 class="text-center"><u>
                PRODI/JURUSAN
            </u></h1>
            <div class="jurusan mt-5 pb-5">
                <div class="row m-3 justify-content-center gap-4">
                    <div class="card col-md-3 rounded-4">
                        <div class="card-body">
                            <img src="../assets/img/tjkt.png" alt="img" class="mt-5">
                            <h5 class="fw-semibold">TJKT</h5>
                            <p>Teknik Jaringan, Komputer dan Telekomunikasi</p>
                        </div>
                    </div>
                    <div class="card col-md-3 rounded-4">
                        <div class="card-body">
                            <img src="../assets/img/pplg.png" alt="img" class="mt-5">
                            <h5 class="fw-semibold">PPLG</h5>
                            <p>Pengembangan Perangkat Lunak dan Gim</p>
                        </div>
                    </div>
                    <div class="card col-md-3 rounded-4">
                        <div class="card-body">
                            <img src="../assets/img/tbsm.png" alt="img" class="mt-5">
                            <h5 class="fw-semibold">TBSM</h5>
                            <p>Teknik dan Bisnis Sepeda Motor</p>
                        </div>
                    </div>
                </div>
                <div class="row m-3 mt-4 justify-content-center mb-5 gap-4">
                    <div class="card col-md-3 rounded-4">
                        <div class="card-body">
                            <img src="../assets/img/dkv.png" alt="img" class="mt-5">
                            <h5 class="fw-semibold">DKV</h5>
                            <p>Desain Komunikasi Visual</p>
                        </div>
                    </div>
                    <div class="card col-md-3 rounded-4">
                        <div class="card-body">
                            <img src="../assets/img/toi.png" alt="img" class="mt-5">
                            <h5 class="fw-semibold">TOI</h5>
                            <p>Teknik Otomasi Industri</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>



    <!-- <div class="container color">
        <div class="row">
            <div class="col">
                
            </div>
        </div>
    </div> -->
</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

.container {
    max-width: 100%;
    margin: 0;
}

h5,
p {
    font-family: "Poppins", serif;
}

.img-fluid {
    margin-top: 57%;

}

/* .kepsek {
    background-color: #0365AE;
} */

.bg {
    background-color: #DFE5E5;
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
    height: 800px;
    width: 100%;
}

.background{
    background-image: url('../assets/img/background.jpeg');
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    padding-top: 5rem;
    width: 100%;
}

.jurusan .card {
    background-color: transparent;
    backdrop-filter: blur(5px);
    border: 3px solid #ffff;
    text-align: center;
}

.card-body h5 {
    margin-top: 30px;
    color: #000;
}

.card-body p {
    font-size: 15px;
}

.card-body img {
    width: 100px;
}

.text-berita p {
    margin-left: 95px;
    max-width: 30%;
}

.card-img-top {
    width: 100%;
    height: 250px;
}

/* .card {
    margin: auto;
    margin-top: 7%;


} */

.layer {
    /* z-index: -3; */
    padding: 0;
}

.layer img {
    z-index: -4;
}


.bg {
    padding: 0;
}


.jumbotron img {
    background: #0365AE;
    border: 3px solid black;
}
</style>