<template>
    <div class="container">
        <div class="row">
            <div class="col d-flex justify-content-center items-center">
                <h2 class="text-white text-center">
                    Organisasi SMK Negeri 4 Tasikmalaya
                </h2>
            </div>
        </div>
        <div class="organisasi">
            <div class="row justify-content-center ">
                <div class="col-3 pt-5 mb-5">
                    <div class="card rounded shadow" style="width: 16rem">
                        <img src="~/assets/img/badmin.png" class="card-img-top mt-3" alt="..." />
                        <div class="card-body">
                            <h3 class="card-title text-center">MPK</h3>
                        </div>
                    </div>
                </div>
                <div class="col-3 pt-5 mb-5">
                    <div class="card rounded shadow" style="width: 16rem">
                        <img src="~/assets/img/badmin.png" class="card-img-top mt-3" alt="..." />
                        <div class="card-body">
                            <h3 class="card-title text-center">OSIS</h3>
                        </div>
                    </div>
                </div>
                <div class="col-3 pt-5 mb-5">
                    <div class="card rounded shadow" style="width: 16rem">
                        <img src="~/assets/img/badmin.png" class="card-img-top mt-3" alt="..." />
                        <div class="card-body">
                            <h3 class="card-title text-center">PUB</h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    max-width: 100%;
}

.col {
    background-image: url("~/assets/img/bg-organisasi.jpg");
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 250px;
    width: 100%;
    display: flex;
    align-items: center;
    margin: auto;
}

.card {
    margin: auto;
}

.card-img-top {
    width: 60%;
    margin: auto;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
    font-family: "Poppins", serif;
    margin: auto;
}
</style>