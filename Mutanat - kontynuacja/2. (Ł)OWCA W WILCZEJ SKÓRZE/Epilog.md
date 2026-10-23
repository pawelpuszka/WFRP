
```dataviewjs
const trackId = "fe04ee50-2f41-4847-bade-092d71d3b341";
const label = "Castle Jam";
const btn = dv.el("button", label);

btn.onclick = async () => {
  new Notice("Wysyłanie żądania do Kenku FM...");

  try {
    await requestUrl({
      url: "http://127.0.0.1:3333/v1/playlist/play",
      method: "PUT",
      headers: { 
        "Content-Type": "application/json" 
      },
      body: JSON.stringify({ 
        id: trackId 
      })
    });

    new Notice("Odtwarzanie rozpoczęte!");
  } catch (err) {
    console.error("Błąd Kenku FM:", err);
    new Notice("Błąd połączenia z Kenku FM!");
  }
};
```

Nadszedł nowy rok a wraz z nim noc wiedźm. Hexennacht. Noc kiedy morslieb jest w pełni i koświetla stary świat swoim chorobliwym, zielono-bladym światłem. Wtedy budzą się nocne koszmary.

**Każdy BG test na Opanowanie - ten z najmniejszą ilością PS ma koszmar.**


```dataviewjs
const trackId = "8de17d5a-c281-4cca-8036-be7e1607bbc8";
const label = "Baldur_S Gate 3 - Quest For A Cure";
const btn = dv.el("button", label);

btn.onclick = async () => {
  new Notice("Wysyłanie żądania do Kenku FM...");

  try {
    await requestUrl({
      url: "http://127.0.0.1:3333/v1/playlist/play",
      method: "PUT",
      headers: { 
        "Content-Type": "application/json" 
      },
      body: JSON.stringify({ 
        id: trackId 
      })
    });

    new Notice("Odtwarzanie rozpoczęte!");
  } catch (err) {
    console.error("Błąd Kenku FM:", err);
    new Notice("Błąd połączenia z Kenku FM!");
  }
};
```

Nie pamiętasz, kiedy zasnąłeś
Twoja świadomość wraca powoli.
Nie widzisz nic. Wokół panuje absolutna, bezdenna ciemność, lecz Twoje ciało odbiera otoczenie z przerażającą precyzją. 
Czy to sen? Gdzie ty jesteś?
Czujesz dotkliwe zimno i wilgoć ściekającą po ścianach z surowego, ciosanego kamienia. W powietrzu unosi się fetor stęchłego moczu, zgnilizny, smrodu przemokniętej sierści. Ta wszystko  przyprawia Cię o mdłości i pali w gardle. 

Stoisz boso w obślizgłym błocie, a zza mroku dobiegają pierwsze dźwięki: odległe, rytmiczne, jakby z głębi ziemi.

<font color="#ff0000">AMBIENT:Distant Drums 1 Lp</font>
W ciemności zaczyna rezonować cichy, głęboki rytm. _Bum... bum... bum..._ – miarowe uderzenia w bębny. Z każdym krokiem, który robisz wbrew własnej woli w głąb ciemnego korytarza, dźwięk gęstnieje. 
Słyszysz piski – tysiące drobnych, wściekłych, chrobotliwych głosów, szelest pazurów drapiących kamień oraz gardłowe, złośliwe skowyty.

Z cienia wyłania się rytmiczny, jednostajny szum – dławiące mruczenie dziesiątek głosów inkantujących bluźniercze litanie w szorstkim, piskliwym języku, od którego cierpnie skóra.

Na zakręcie tunelu mrok zaczyna ustępować. Zza krawędzi skał sączy się nienaturalny, jarzący się, pulsujący **zielony blask**. Promieniuje uderzeniami gorąca i chorobliwym zielonym światłem. Twoja jaźń podąża w jego stronę. Nie potrafisz nad tym zapanować.



<font color="#ff0000">MUZYKA: ROGATY SZCZUR - Vermintide End Times</font>
Wkraczasz do ogromnej, sklepionej pieczary. Zielone światło bije z potężnego, pękniętego kryształu zawieszonego nad ołtarzem z czaszek. Wokoło krążą w powolnym, hipnotycznym tańcu setki garbatych, kudłatych postaci o czerwonych, błyszczących ślepiach.

<font color="#ff0000">0:30</font>
Na wzniesieniu, otoczony przez zgarbione postaci wyglądające jak szamani z kosturami, stoi **Hector Wolf**.

Oni nie poniewierają nim. Skłaniają przed nim swoje pyski w szaleńczym, religijnym dziękczynieniu. Wolf nosi na sobie rytualne, szare płaty skórzanych szat przymocowane mosiężnymi klamrami, a na jego szyi wisi kościany symbol Rogatego Szczura. Jest wywyższony – przyjęty do panteonu ich ulubionych, najcenniejszych narzędzi.
 


Nagle ruch w pieczarze zamiera. Pisk i bębny milkną. Zielone światło błyszczy do granic możliwości.

<font color="#ff0000">MUZYKA: ROGATY SZCZUR - The Wizard's Tower - Jesper Kyd</font>
Przestrzeń gwałtownie się załamuje. Podłoże znika pod Twoimi stopami, a **twarz Hectora Wolfa pojawia się tuż przed Tobą** – cale od Twoich oczu, tak blisko, że czujesz na twarzy jego zimny, cuchnący, kwasowy oddech.

Widzisz każdy przerażający detal:

Głębokie bruzdy na jego twarzy pulsują  zielonkawym światłem, jakby pod skórą pełzały cienkie robaki. Jego oczy  zwęziły się w pionową, gadzią źrenicę, a skóra wokół ust jest popękana i zakrwawiona.

Hector patrzy ci prosto w oczy z wyrazem absolutnego, chłodnego triumfu i nienawiści. Nagle otwiera usta, a jego głos – mieszanka ludzkiego tonu i gardłowego, szczurzego syku – rezonuje bezpośrednio w Twojej głowie:

> „Myśleliście, że zabiliście go w mroku Ubersreiku...  Śliski Kuba to nie ciało... to wola! Śliski Kuba nie żyje? Nie!!! Niech żyje Śliski Kuba!”

Twarz Hectora wykrzywia się w potwornym uśmiechu, a jego paszcza rozwiera się nierealistycznie szeroko, wręcz karykaturalnie, ukazując rzędy ostrych kłów.

Nagły rozblask zielonego światła oślepia Cię całkowicie, a Ty budzisz się na posłaniu oblany zimnym potem.

To był tylko sen.

Prawda?