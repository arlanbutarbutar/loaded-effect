# loaded-effect
Loading Animation for Web Pages

Animasi loading untuk tampilan web kamu.
Kamu bisa edit bagian script JS untuk melakukan redirect dan membuat object lainnya untuk menunda waktu tampil ke halaman web utama kamu

🖌custom code
  // JavaScript
  👉<script>
      var loader = document.getElementById('loader');
        window.addEventListener('load', function(){
          loader.style.display="none";
          ...
      });
    </script>
