<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
 

h1 {
            color: #333;
        }

 h2 {
            color: #555;
        }

  p {
            color: #666;
            line-height: 1.4;
        }

 pre {
            background-color: #f7f7f7;
            padding: 10px;
            border: 1px solid #ddd;
        }

 code {
            font-family: "Courier New", monospace;
            background-color: #f7f7f7;
            padding: 2px 4px;
            border: 1px solid #ddd;
        }

 ul {
            list-style-type: disc;
            margin-left: 20px;
        }

li {
            margin: 5px 0;
        }
</style>
</head>
<body>
    <!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1>Arch Linux Masaüstü Ortamı Kurulumu Rehberi</h1>

<p>Merhaba Linux severler!</p>

 <p>Bugünkü yazımızda sizlere Arch Linux'a masaüstü ortamı kurmanızı anlatacağım. Arch Linux, minimalist bir yaklaşım sunar ve varsayılan olarak masaüstü ortamı sunmaz, ancak size tam kontrol sağlar. Bu nedenle, kendi masaüstü ortamınızı özelleştirebilirsiniz. İşte adım adım rehberimiz:</p>

 <h2>Adım 1: Arch Linux Kurulumu</h2>

<p>İlk adım olarak, Arch Linux'u kurmanız gerekiyor. Arch Linux kurulumu oldukça özelleştirilebilir ve bu işlemi tamamlamak için <a href="https://wiki.archlinux.org/title/Installation_guide" target="_blank">Arch Linux Kurulum Kılavuzu</a> size yardımcı olacaktır.</p>

 <h2>Adım 2: Temel Paketleri Güncelleme</h2>
    <p>Sisteminizi güncel tutmak önemlidir. Bu nedenle, kurulum tamamlandıktan sonra aşağıdaki komutu kullanarak temel paketleri güncelleyin:</p>

 <pre><code>sudo pacman -Syu</code></pre>

  <h2>Adım 3: Xorg Grafik Sunucusunu Kurma</h2>

 <p>Masaüstü ortamı kullanabilmek için Xorg grafik sunucusunu kurmalısınız:</p>

  <pre><code>sudo pacman -S xorg</code></pre>

 <h2>Adım 4: Ekran Kartı Sürücüsü Kurulumu (isteğe bağlı)</h2>

 <p>Eğer özel bir ekran kartı kullanıyorsanız, sürücülerini kurmanız gerekebilir. Örneğin, NVIDIA ekran kartı kullanıyorsanız, NVIDIA sürücülerini kurmak için aşağıdaki komutu kullanabilirsiniz:</p>

<pre><code>sudo pacman -S nvidia</code></pre>

<h2>Adım 5: Masaüstü Ortamı Seçimi</h2>

<p>Arch Linux için birçok farklı masaüstü ortamı seçeneği bulunmaktadır. İşte bazı popüler seçenekler:</p>

 <ul>
        <li>GNOME: Kullanımı kolay ve modern bir masaüstü ortamı.</li>
        <li>KDE Plasma: Güçlü ve özelleştirilebilir bir masaüstü ortamı.</li>
        <li>Xfce: Hafif ve hızlı bir masaüstü ortamı.</li>
        <li>LXQt: Hafif ve özelleştirilebilir bir masaüstü ortamı.</li>
        <li>i3: Tiling pencere yöneticisi ile minimalist bir yaklaşım.</li>
    </ul>

 <h2>Adım 6: Masaüstü Ortamını Kurma</h2>

  <p>Seçtiğiniz masaüstü ortamını kurmak için aşağıdaki komutu kullanabilirsiniz. Örneğin, GNOME masaüstü ortamını kurmak için:</p>

 <pre><code>sudo pacman -S gnome</code></pre>

<h2>Adım 7: Oturum Yöneticisi (Display Manager) Kurma</h2>

 <p>Masaüstü ortamını başlatmak için bir oturum yöneticisi kurmanız gerekebilir. Örnek olarak, LightDM oturum yöneticisini kurmak için aşağıdaki komutu kullanabilirsiniz:</p>

 <pre><code>sudo pacman -S lightdm</code></pre>

<h2>Adım 8: Oturum Yöneticisini Etkinleştirme</h2>

 <p>Oturum yöneticisini etkinleştirin ve sistem başladığında otomatik olarak başlamasını sağlamak için aşağıdaki komutu kullanın:</p>

<pre><code>sudo systemctl enable lightdm</code></pre>

<h2>Adım 9: Sistemi Yeniden Başlatma</h2>

<p>Son olarak, sistemi yeniden başlatın ve masaüstü ortamınızı kullanmaya başlayabilirsiniz:</p>

 <pre><code>sudo reboot</code></pre>

 <p>Artık Arch Linux üzerinde kendi masaüstü ortamınızı kullanabilirsiniz. Arch Linux size özgürlük ve özelleştirme imkanı sunar, bu nedenle yeni bir deneyime hazır olun!</p>

<p>Umarım bu rehber, Arch Linux'a masaüstü ortamı kurmanıza yardımcı olur. Herhangi bir sorunuz varsa, lütfen bize bildirin. İyi eğlenceler ve başarılar dileriz!</p>
</body>
</html>

</body>
</html>
