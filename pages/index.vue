<template>
    <div class="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6 box ">
                <nuxt-link to="../pengunjung/tambah">
                    <div class="card bg-pengunjung rounded-5">
                        <div class="card-body">
                            <h2>Pengunjung</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
            <div class="col-lg-6 box">
            <nuxt-link to="../buku">
                    <div class="card bg-buku rounded-5">
                        <div class="card-body">
                            <h2>Cari Buku</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </div>
    <h2 style="margin: 30px;"><strong>STATISTIK</strong></h2>
    <div class="container-fluid">
    <div class="row justify-content-evenly rounded-3">
        <div class="col-5">
            <div class="card1">
                <div class="syifa">
                    <h2>3 Pengunjung</h2>
                </div>
            </div>
        </div>
        <div class="col-5">
            <div class="syifa1">
                <h2>30 Buku</h2>
            </div>
        </div>
    </div>
    </div>
    <div class="line">
    <Statistik />
    </div>
</template>

<style scoped>
.v2 {
    height: 3px;
    width: 98%;
    margin-left: 30px;
    border-left: 3px solid black;
    background-color: black;
}
.v1 {
    margin-top: 40px;
    margin-left: 30px;
    border-left: 3px solid black;
    height: 400px;
}
.card {
    height: 200px;
    box-shadow: 1px 1px 5px #45AAB8;
}
.card.bg-pengunjung {
    background-image: url('../assets/img/Picture1.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}
.card.bg-buku {
    background: url('../assets/img/Picture2.png') no-repeat center center;
    background-size: cover;
}
.syifa {
    height: 200px;
    box-shadow: 1px 1px 10px;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #D4EBDC;
}
.syifa1 {
    height: 200px;
    box-shadow: 1px 1px 10px;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #A6E9E1;
}
.card-body h2{
    color: black;
}
.box {
    width: 50%;
}
.box a{
    text-decoration: none;
}
</style>