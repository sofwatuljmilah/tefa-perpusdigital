<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4"> CARi BUKU</h2>
                <div class="my-3">
                    <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?">
                 </div>
                 <div class="my-3 text-muted text-white">Menampilkan 3 dari 3</div>
                 <div class="row">
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <nuxt-link to="/buku/des">
                                <div class="card-body">
                                    <img src="~/assets/img/poto1.jpeg" class="cover" alt="poto1">                          
                                </div>
                            </nuxt-link>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/poto2.jpg" class="cover" alt="poto2">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~assets/img/poto3.jpeg" class="cover" alt="poto3">
                            </div>
                        </div>
                    </div>

                 </div>
            </div>
        </div>
    </div>

    <div class="d-flex justify-content-end"  >
                <nuxt-link to="/" class="btn btn-primary btn-lg text-dark rounded-5 px-5">
                    KEMBALI
                </nuxt-link>
    </div>
</template>

<style scoped>
.card-body{
    width: 100%;
    height: 20rem;
    padding: 0;
}

.cover{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: 0;
}
.btn-primary {
    background-color: #4B7CAA !important;
}
</style>