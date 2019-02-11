# JavascriptGetParameterUrl
Cara Mendapatkan Method GET Url dengan Javascript

Contoh URL Anda
http://[::1]/baznas.bengkuluselatan/mmustahik?nik=17010509099xxxxx&&nama=HERU%20PRASETYO

Copykan Code ini ke lembar kerja anda
<script>
var sURL = window.document.URL.toString();  //Get All Parameter URL
var url = new URL(sURL); //new Output sUrl
var nik = url.searchParams.get("nik"); //Get Parameter URL nik
console.log(nik);
</script>
