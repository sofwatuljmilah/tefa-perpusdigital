<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
                <div class="my-3">
                    <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
                </div>
                <div class="my-3 text-muted">menampilkan 3 dari 3</div>
                <table class="table">
                    <thead>
                        <tr>
                            <td>NO</td>
                            <td>NAMA</td>
                            <td>KEANGGOTAAN</td>
                            <td>WAKTU</td>
                            <td>KEPERLUAN</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1.</td>
                            <td>Sofwatul</td>
                            <td>Siswa</td>
                            <td>26 Februari 2024, 9.05.00</td>
                            <td>Baca</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
         <div class="col-5 "  >
            <nuxt-link to="/" class="btn bg-secondary btn-lg rounded-5 px-5 text-dark">
                    KEMBALI
                </nuxt-link>
                </div>

</template>

<style scoped>
.bg-secondary {
    background-color: #4B7CAA !important;
}
</style>