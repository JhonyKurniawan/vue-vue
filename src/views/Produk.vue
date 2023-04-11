<template>
  <div class="produk">

  </div>

  <center>  <h3>Baju Pria</h3>
    <table >
      <tr>
        <th>Baju Kaos</th>
        <th>Merek </th>
        <th>Size</th>
        <th>Baju Kemeja</th>
        <th>Merek </th>
        <th>Size</th>
      </tr>


      <tr>
        <td><img src="/kaos.jpg" alt="baju kaos" style="width:200px;height:220px;" /></td>
        <td align="center">Bombboogie</td>

        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>

        <td><img src="/kemeja.jpg" alt="baju kemeja" style="width:200px;height:220px"/> </td>
        <td align="center">Kemeja Flanel</td>

        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>
      </tr>

      <tr>
        <td><img src="/kaos2.jpg" alt="baju kaos 2" style="width:200px;height:220px;" /></td>
        <td>Calcius Casual</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option disabled value="">Pilih Size Baju</option>
              <option>M</option>
              <option>L</option>
              <option>XL</option>
              <option>XXL</option>
            </select></td>
        <td><img src="/kemeja2.jpg" alt="baju kemeja" style="width:200px;height:220px"/> </td>
        <td align="center">Kemeja casual</td>

        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>
      </tr>

    </table>


    <h4>Celana Pria</h4>
    <table >
      <tr>
        <th>Celana Jeans</th>
        <th>Merek </th>
        <th>Size</th>
        <th>Celana Training</th>
        <th>Merek </th>
        <th>Size</th>
      </tr>


      <tr>
        <td><img src="/jeans.jpg" alt="celana jeans" style="width:200px;height:220px;" /></td>
        <td align="center">jeans</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>

        <td><img src="/training.jpg" alt="celana training" style="width:200px;height:220px"/> </td>
        <td align="center">Celana Jogger</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>
      </tr>

      <tr>
        <td><img src="/jeans2.jpg" alt="celana jeans 2" style="width:200px;height:220px;" /></td>
        <td>Calcius Casual</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>

        <td><img src="/training2.jpg" alt="celana training 2" style="width:200px;height:220px"/> </td>
        <td align="center">Adidas</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Size Baju</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
          <option>XXL</option>
        </select></td>
      </tr>

    </table>
    <h5>Jam Tangan</h5>
    <table>
      <tr>
        <th>Jam Tangan</th>
        <th>Merek</th>
        <th>Warna</th>
      </tr>

      <tr>
        <td> <img src="/jam.jpg" alt="jam tangan" style="width:200px;height:220px"/></td>
        <td>Jam Digital</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Warna</option>
            <option>Hitam</option>
            <option>Biru</option>
            <option>Putih</option>
            <option>Merah</option>
          </select></td>
      </tr>

      <tr>
        <td> <img src="/jam2.jpg" alt="jam Tangan 2" style="width:200px;height:220px"/></td>
        <td>Rantai Silver</td>
        <td><select class="form-select form-select-sm" aria-label=".form-select-sm example">
          <option disabled value="">Pilih Warna</option>
            <option>Hitam</option>
            <option>Putih</option>
            <option>Emas</option>
            <option>silver</option>
          </select></td>
      </tr>
    </table>

    <div>
      <a href="https://shopee.co.id/search?keyword=baju%20kaos" target="_blank">Lebih lengkap nya klik disni</a>
    </div>

    <span>Keritik dan saran untuk toko kami:</span>
    <p style="white-space: pre-line;">{{ pesan }}</p>
    <br>
    <textarea v-model="pesan" placeholder="Kirim pesan" ></textarea>
    <h6>
      Tentang Kami
    </h6>
    <p>
      Toko Baju menawarkan transaksi jual beli online yang menyenangkan, gratis, dan terpercaya. Bergabunglah dengan jutaan pengguna lainnya dengan mulai mendaftarkan produk jualan dan berbelanja berbagai penawaran menarik kapan saja, di mana saja. Keamanan transaksi kamu terjamin.. Ayo gabung dalam komunitas dan mulai belanja sekarang!
    </p>
  </center>


</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>

table, th, td {
  border:2px solid #dfa852;}

</style>

<style>
body {
  font-size: 20px;
}


</style>

