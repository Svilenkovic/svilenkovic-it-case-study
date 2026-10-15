<a href="https://svilenkovicit.com/"><img src="media/cover.jpg" alt="Svilenković IT, naslovna strana na laptopu i telefonu" width="100%"></a>

# Svilenković IT

Domen, DNS, poslovni mejl i sertifikat objašnjeni bez žargona, uz proveru DNS zapisa koja radi u pregledaču posetioca.

**[svilenkovicit.com](https://svilenkovicit.com/)** · [Studija slučaja](https://svilenkovic.rs/radovi/svilenkovic-it) · [English](README.md)

> [!NOTE]
> Moj sopstveni projekat, ne klijentski posao. Izvorni kod je privatan. Ova stranica opisuje šta sajt radi i kako je napravljen.

<table>
  <tr><td><b>Klijent</b></td><td>Sopstveni projekat</td></tr>
  <tr><td><b>Delatnost</b></td><td>Domen, poslovni mejl i sigurnost sajta</td></tr>
  <tr><td><b>Lokacija</b></td><td>Srbija</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana i proverom DNS zapisa</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Istraživanje, dizajn, izrada, SEO i hosting</td></tr>
  <tr><td><b>Tehnologije</b></td><td>Astro 7, GSAP, DNS-over-HTTPS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## O projektu

Mala firma o domenu i pošti obično razmišlja tek kad mejlovi počnu da idu u spam ili kad domen istekne. Svilenković IT objašnjava delove koji rade u pozadini, pisano za vlasnika firme, ne za administratora. Svaka strana je jedan list, kao na nacrtu instalacije, sa brojem lista, razmerom i datumom revizije, i odgovara na jedno pitanje, od mejlova u spamu do toga šta raditi kad je sajt hakovan.

Provera DNS zapisa pita javni DNS za NS, A, AAAA, MX, SPF, DKIM, DMARC, CAA i DNSSEC i uz svaki nalaz na srpskom kaže da li je u redu. Upiti idu preko DNS-over-HTTPS direktno iz pregledača posetioca ka Cloudflare-u ili Google-u, pa ni domen ni rezultat ne stižu na moj server, a politika sadržaja dozvoljava vezu samo sa ta dva servisa.

## Šta sam uradio

- Provera DNS zapisa koja hvata i SPF sa više od deset DNS upita, dva SPF zapisa na istom domenu i DMARC oznake koje više ne važe
- Šema puta jednog mejla koju iscrtava GSAP, a lažna poruka na njoj ne prođe SPF, DKIM i DMARC
- GSAP se učitava tek kad šema uđe u ekran, a bez skripte ili uz smanjeno kretanje šema odmah stoji nacrtana
- Posebne strane za domen, DNS, poslovni mejl, sertifikat, rezervne kopije i hakovan sajt
- Kontakt forma sa proverom unosa i ograničenjem broja zahteva

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, oktobar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `FAQPage`, `Organization`, `Person`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Svilenković IT, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Svilenković IT, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Provera DNS zapisa sa ocenom svakog zapisa">
<sub>Provera DNS zapisa sa ocenom svakog zapisa</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
