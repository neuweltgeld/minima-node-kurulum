# minima-node-kurulum

Linux VPS makineler için kurulumun resmi kaynaktan bireysel çevirisidir.

orjinal kaynak https://www.minima.global/run-a-node



Root kullanıcı olarak sunucunuza giriş yapın

Komut penceresini açıp root dizininde olduğunuza emin olun

Minimanın eski sürümlerinden birini kullanıyorsanız sonraki adıma geçmeden önce aşağıdaki komutla silme işlemini gerçekleştirin <br>

<code>
wget -O minima_cleanup_v98.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_cleanup_v98.sh && chmod +x minima_cleanup_v98.sh && sudo ./minima_cleanup_v98.sh
</code>


<br>
<br>
<br>
Root dizininde bu kodu çalıştırın<br>
<code>
wget -O minima_setup.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_setup.sh && chmod +x minima_setup.sh && sudo ./minima_setup.sh -r 9002 -p 9001
</code>

Minimanın çalışmasını bekleyin, bu bazı durumlarda 30 dakikayı bulabilir.
