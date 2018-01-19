---
ID: 1549
post_title: Zpřístupnění práce
author: admin
post_excerpt: ""
layout: help
permalink: >
  https://lab.urad.online/help/making-your-work-accessible/
published: true
post_date: 2018-01-15 22:52:07
help_tags:
  - Nepřiřazeno
help_category:
  - Pro všechny
---
<h3>Zpřístupnění práce</h3>
Webová dostupnost znamená, že lidé s postižením mohou používat web. Konkrétně to znamená, že lidé s postižením mohou vnímat, pochopit, navigovat a komunikovat s webem a že mohou přispívat na web. Přístupnost webu také prospívá ostatním, včetně starších lidí s měnícími se schopnostmi v důsledku stárnutí (z <a href="https://www.w3.org/WAI/intro/accessibility.php">iniciativy Web Accessibility Initiative</a> ). Zavedení dostupných návrhových standardů často zlepší zážitek každého, kdo používá vaše stránky.

Níže uvedený příspěvek načrtává, co byste měli udělat, abyste zlepšili přístupnost na svých stránkách kurzu, projektu, klubu a portfolia. Další informace o dostupnosti a vylepšeních, které společnost OpenLab vytváří, naleznete v našem příspěvku o  <a href="https://lab.urad.online/help/summary-of-accessibility-on-the-openlab/">souhrnu dostupnosti OpenLab</a> . Stránka CUNY o standardech přístupnosti má rovněž užitečné informace o <a href="http://www2.cuny.edu/accessibility/content/">zpřístupnění digitálního obsahu</a> .
<h4>Dokumenty</h4>
Je důležité, aby dokumenty, jako jsou soubory PDF a Microsoft Word, které jste nahrali do OpenLab, byly přístupné. Patří sem dokumenty na webu nebo v sekci Soubory profilu kurzu, projektu nebo klubu. Příručka CUNY k <a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/">vytváření dostupných dokumentů PDF a Microsoft Office</a> poskytuje podrobné pokyny, jak to udělat, ale několik klíčových bodů je zdůrazněno níže.
<ol>
 	<li>Soubory PDF jsou nejobtížnější souborový formát, který zpřístupňuje a správně strukturovaný kód HTML je nejvíce dostupný.
<ul>
 	<li>Použijte nebo odkazujte na PDF pouze v případě, že nelze použít soubory HTML nebo Microsoft Office.</li>
 	<li>Zajištění prohledávatelného textu a označování PDF se skrytými štítky (značky), které popisují strukturu dokumentu, jsou minimální požadavky na přístupnost dokumentů PDF, aby byly správně čteny čtečkou obrazovky.</li>
</ul>
</li>
 	<li>Pokud je nutné použít PDF, postupujte podle pokynů CUNY pro:
<ul>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#Save">Uložení dokumentu aplikace Word jako PDF</a></li>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#pdf_scanned">Použití naskenovaného dokumentu PDF</a></li>
 	<li><a href="http://www2.cuny.edu/accessibility/content/pdf-microsoft/#pdf_forms">Použití formulářů PDF</a></li>
</ul>
</li>
</ol>
<h4>snímky</h4>
<ol>
 	<li>Zahrnout alternativní text pro všechny obrázky. Kdykoli přidáte nový snímek do příspěvku nebo stránky, do pole <strong>Alt Text</strong>vložte krátký text do pole pro vložení média (zobrazí se na následujícím obrázku obrazovky).
<ul>
 	<li>Nezahrnujte slova "fotka" nebo "obrázek", protože čtečka obrazovky již signalizuje, že jde o obrazový soubor. Uchovávejte popis krátký a informativní.</li>
 	<li>U snímků, které představují koncepty a informace, například fotografie a ilustrace, je třeba uvést jiný text, který krátce předává základní informace, které obrázek představuje. Další informace o alt textu pro různé typy obrázků naleznete  <a href="http://www2.cuny.edu/accessibility/content/websites/#images">v příručce CUNY pro přístupnost obrázků</a> .</li>
 	<li>Odůvodnění: Alternativní text nebo "alt text" zkratka odkazuje na krátký popis obrázků, které budou číst nahlas čtenáři obrazovky, a je vyžadován pro přístupnost.</li>
</ul>
</li>
 	<li>Odstraňte libovolný text v poli <strong>Název</strong> .
<ul>
 	<li>Odůvodnění: WordPress automaticky vytvoří název obrázku, který je shodný s názvem souboru obrázku. Obvykle to vede k bezvýznamnému názvu, jako je "IMG_5981". Tituly jsou volitelná a některé prohlížeče nebo zařízení nemusí podporovat, takže je lepší zahrnout pouze alt text a vyhnout se čtečce na obrazovce buď chybějící titul nebo čtení stejných informací dvakrát.</li>
</ul>
</li>
 	<li>Obrázků zabránit otevření v jejich záložce vlastní po klepnutí výběrem <strong>nic</strong> v <strong>Odkaz na</strong> menu.
<ul>
 	<li>Odůvodnění: Snímky nebudou mít při otevření v novém okně žádný jiný text nebo jiné ovládací prvky přístupnosti.</li>
</ul>
</li>
</ol>
&nbsp;

<img class="alignnone size-full wp-image-45616" src="https://openlab.citytech.cuny.edu/wp-content/uploads/2017/10/Alt_Text_1.png" alt="Snímek obrazovky zobrazující název, alt text a odkaz na nastavení." />
<h4>Video a animace</h4>
<ol>
 	<li>Neprovádějte automatické přehrávání videa a animovaných gifů s blikajícím vizuálním obsahem.
<ul>
 	<li>Odůvodnění: Lidé, kteří používají čtečky obrazovky, mohou mít potíže se slyšet výstup čtenáře, pokud se současně přehrává jiný zvuk.</li>
 	<li>Odůvodnění: Rychle blikající nebo blikající obrázky mohou způsobit záchvaty u osob s určitými typy záchvatových onemocnění.</li>
 	<li>Odůvodnění: Animace mohou být dezorientovány u mnoha lidí, zejména u těch, kteří mají určité typy kognitivních poruch.</li>
</ul>
</li>
 	<li>Zahrnout titulky pro video. Titulky poskytují textové verze slov ve videu. Je to zásadní pro lidi, kteří nemohou slyšet zvuk, a mohou být užiteční pro všechny uživatele vašeho webu, včetně lidí, kteří neublížili jazyku používanému ve videu / zvuku, nebo lidé, kteří pracují v klidném prostředí.
<ul>
 	<li><a href="https://www.youtube.com/">YouTube</a> a <a href="https://vimeo.com/">Vimeo</a> jsou navrhované video platformy pro OpenLab a oba umožňují přidat titulky. YouTube poskytuje pokyny pro  <a href="https://support.google.com/youtube/answer/2734796?hl=en">přidání vlastních titulků a titulků</a>  a Vimeo má také nápovědu k  <a href="https://help.vimeo.com/hc/en-us/articles/224968828-Captions-and-subtitles">titulkům a titulkům</a> .</li>
 	<li>Informace o dalších nástrojích naleznete v příručce CUNY pro <a href="http://www2.cuny.edu/accessibility/content/videos/#video_captioning_tools">nástroje pro popis obrázků</a> .</li>
</ul>
</li>
</ol>
<h4>Organizace stránek<strong>
</strong></h4>
<h5>Odkazy</h5>
<ol>
 	<li>Použijte informativní a specifické znění pro text, na který uživatel klepne, a popište, kde bude odkaz přijímat. Například pokud odkazujete na článek o přístupnosti, použijte popisný text, například "Článek o přístupnosti".
<ul>
 	<li>Vyvarujte se nejasných frází typu "klikněte sem".</li>
 	<li>Nepoužívejte slovo "odkaz", protože čtečky obrazovky již upozorní uživatele, že text je odkaz.</li>
 	<li>Nepoužívejte adresy URL v textu odkazu, protože jsou nahlas čteny nahlas. Např. "W3C Tutorial na funkčních obrázcích" spíše než "https://www.w3.org/WAI/tutorials/images/functional".</li>
 	<li>Odůvodnění: Pokud někdo používá čtečku obrazovky, která bude hlasitě číst odkazy, uživatel bude moci vědět, kam bude mít odkaz předtím, než klikne.</li>
</ul>
</li>
</ol>
<h5>Návrh informací</h5>
<ol>
 	<li>Uspořádejte obsah v příspěvku nebo stránce pomocí nadpisů a uspořádat informace, které předkládáte, abyste vytvořili jasnou vizuální hierarchii.
<ul>
 	<li>Odůvodnění: pomocí logické struktury budete mít prospěch všem, kteří navštíví vaše stránky. Informace lze snadno vyhledávat pro zrakově postižené uživatele. Lidé, kteří používají čtečky obrazovky, mohou používat okruhy pro navigaci mezi různými sekcemi.</li>
</ul>
</li>
 	<li>Použijte styly Heading v rozbalovací nabídce Post nebo v editoru stránek namísto tučné nebo kurzívy, které označují nadpis (viz obrázek níže).
<ul>
 	<li>Styl Nadpis 1 by měl být použit pouze jednou na stránku. Nepoužívejte styly nadpisu 2 příliš často; měly by být vyhrazeny pouze pro názvy dílčích sekcí.</li>
</ul>
</li>
 	<li>Používejte běžné rozpoznatelné písma, které poskytují silný kontrast s barvou pozadí stránky. To nebude problém pro většinu členů OpenLab, pokud se držíte výchozích písem a barev pro váš motiv. Pokud však používáte některý z našich pluginů pro písmo, jako například jednoduché písma Google nebo změníte barvy textu nebo pozadí, naleznete další informace o kontrastu ve <a href="https://webaim.org/articles/visual/lowvision#highcontrast">službě WebAim: Vizuální postižení: Vysoký kontrast</a> .
<ul>
 	<li>Nepoužívejte barvy, které vytvářejí malý kontrast; například světlé barvy písma na bílém pozadí.</li>
 	<li>Vyhněte se skriptovým písmům, které mohou být obtížné číst pro všechny; a zejména lidí se zrakovým postižením.</li>
 	<li>Zkuste prohlížet své stránky při zvětšování, což je běžná praxe ke zvýšení čitelnosti. Můžete to provést stisknutím kláves ctrl a + nebo příkazem + na počítači Mac.</li>
</ul>
</li>
</ol>
&nbsp;

<img class="alignnone size-full wp-image-45617" src="https://openlab.citytech.cuny.edu/wp-content/uploads/2017/10/Headings_2.png" alt="Snímek zobrazující styly nadpisů" />
<h4>Dodatečné zdroje</h4>
Níže uvádíme další užitečné zdroje, jak zpřístupnit vaše stránky:
<ul>
 	<li><a href="http://blogaccessibility.com/a-super-simple-way-to-make-images-accessible-alt-text-versus-title-explained/">Jednoduchý jednoduchý způsob, jak zpřístupnit obrazy: Vysvětlený text Alt versus Název</a></li>
 	<li><a href="https://www.w3.org/WAI/tutorials/images/functional/">W3C výuka na funkčních obrázcích</a></li>
 	<li><a href="http://www.interactiveaccessibility.com/blog/making-images-visible-blind-users#.WAfrZNwqH8U">Vytváření snímků viditelných pro nevidomé uživatele</a></li>
 	<li>CUNY Průvodce pro přístupné <a href="http://cats.cuny.edu/reasonableaccommodations/TechnologyintheClassroom.html">technologie v učebně a pro on-line kurzy</a></li>
 	<li><a href="https://er.educause.edu/articles/2017/1/ada-compliance-for-online-course-design">Shoda ADA pro návrh kurzů online</a></li>
 	<li><a href="http://wave.webaim.org/">Nástroj pro vyhodnocování dostupnosti webu</a> (WAVE) - lze použít k nalezení chyb na přístupnosti na vašem webu</li>
 	<li><a href="https://webaim.org/resources/contrastchecker/">Kontrola barevného kontrastu WebAIM</a> - lze použít k ověření barevných kontrastů, které odpovídají standardům přístupnosti</li>
</ul>