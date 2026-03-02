<h1 aling="center">OSE 🌀 Bypass</h1>
Ogólnopolski system edukacji czyli <b>OSE</b> jest systemem administracyjnym dla szkół który blokuje niektóre strony te "słuszne" i nie takie jak YT czy VSCode online.
<h2>Usługi OSE:</h2>
 • <b>OSE Internet 🛜 </b> (Katalogowanie, blokoenie przez DNS oraz internet za free dla szkół)<br>
 • <b>Certyfikat OSE 🔗</b> (Aplikacja na komputer szkolny do weryfikacji czy komputer jest ze szkoły)

<h2>Jak OSE blokuje strony?</h2>

<p>
OSE blokuje strony na poziomie usługi <b>"OSE Internet for School"</b>. 
Działa to w pewnym sensie podobnie do VPN, choć technicznie nie jest to klasyczny VPN. 
Najprostsze porównanie wygląda tak:
</p>

<p><b>VPN:</b><br>
Komputer → DNS → Komputer użytkownika → VPN → Strona internetowa
</p>

<p><b>OSE:</b><br>
Komputer → DNS → Centralny serwer OSE 
(weryfikacja, czy strona jest zablokowana oraz analiza informacji o sieci i komputerze) 
→ Komputer → 
</p>

<ul>
<li>Jeśli DNS nie jest zablokowany → Strona internetowa otwiera się normalnie</li>
<li>Jeśli DNS jest zablokowany → OSE podmienia plik <code>index.html</code> na stronę z komunikatem o blokadzie podczas przesyłania danych</li>
</ul>