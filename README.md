# Counter-Strike: Source Full Mod (YAKINDA)

Bu, Counter-Strike: Source (CS:S) oyun sunucuları için çeşitli oyun modlarını içeren eksiksiz bir mod paketi sunar.

## **Amaç:**
Counter-Strike 2 oynamak istemeyen veya sıkılan kişiler için, Counter-Strike: Source üzerinden CSS Full Mod sunucusu açmak, nostaljik bir deneyim sunmanın yanı sıra birçok avantaj da sağlar. Bu sunucuyu açarak, daha düşük dosya boyutlarıyla, eski oyun tarzının keyfini çıkarabilir ve sistem gereksinimlerini azaltabilirsiniz. Ayrıca, bu sunucu dosyalarını kendi bilgisayarınızda da kolayca kurarak, bireysel bir oyun deneyimi yaşayabilirsiniz.

İçerik:
- Aim
- AWP
- Deathrun
- Jailbreak
- Minigames
- Surf
- Seek
- Training (Jailbreak)

## Bilinmesi Gerekenler:
```sh
Sunucuyu ilk açtığınızda, haritayı yeniden başlatmanızda fayda var. Nadir de olsa, bazı pluginler düzgün yüklenmeyebilir.
Jailbreak modunda, SKZ (Süreli KZ) ayarlamak için `!zones` komutunu kullanarak SKZ adında bir bölge oluşturabilirsiniz. Daha fazla SKZ için (SKZ1, SKZ2) şeklinde bölge oluşturabilirsiniz.
Jailbreak Training haritasında, `!zones` komutuyla başlangıç ve bitiş noktalarını belirleyebilirsiniz. Ayrıca, `!saveruns` ve `!savezones` komutları ile bölgeleri kayıt edebilirsiniz.
```

```sh
Counter-Strike: Source oyununda sürekli mikrofon açık bırakma özelliği bulunmadığı için, Jailbreak modunda komutçu olan oyuncuların kendi oyun dosyalarına .cfg dosyası oluşturarak aşağıdaki komutu eklemesi gerekir:

alias mike "mikeon"
alias mikeon "+voicerecord; alias mike mikeoff"
alias mikeoff "-voicerecord; alias mike mikeon"

bind "F9" "mike"

Bu ayar sayesinde F9 tuşuna bastığınızda mikrofonunuz sürekli açık kalır. Tekrar bastığınızda ise mikrofon kapanır.
```

## **Config Dosyaları:**

```sh
cfg\server.cfg: Sunucu adını buradan değiştirebilirsiniz.
cfg\mapcycle.txt: Sunucunuzda yüklü olan haritaları bu dosyada belirleyebilirsiniz.
addons\sourcemod\configs\sm_changesmtag.cfg: Sunucu tagını buradan değiştirebilirsiniz.
addons\sourcemod\configs\admin_levels.cfg: Hangi bayraklara hangi yetkilerin atandığını bu dosyada öğrenebilirsiniz.
addons\sourcemod\configs\hextags.cfg: Yetkililere veya oyunculara tag atamak için bu dosyayı kullanabilirsiniz.
addons\sourcemod\configs\wardencommands.cfg: Komutçunun kullanabileceği komutları bu dosyaya ekleyebilirsiniz.
addons\sourcemod\configs\helpmenu.cfg: Sunucu kurallarını ve komutlarını düzenleyebilirsiniz.
addons\sourcemod\configs\chatblocker: Belirli kelimeleri yasaklamak veya izin vermek için kullanabilirsiniz.
addons\sourcemod\configs\map-cfg: Belirli eklentileri eklemek veya kaldırmak için kullanabilirsiniz.
```
