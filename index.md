<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anand Murugesan - Associate Professor of Economics</title>
    <link rel="stylesheet" href="style.css">
    </head>
<body>

    <div class="container">

        <header>
            <h1>Associate Professor of Economics</h1>
            <p>[<a href="https://people.ceu.edu/anand_murugesan">Department of Public Policy</a>], [<a href="https://www.ceu.edu/vienna">Central European University, Vienna</a>]</p>
            <p>B-412, Quellenstraße 51, 1100 Vienna</p>
            <p>Phone: +43.1.25230.2054</p>

            <h2>Senior Researcher</h2>
            <p>[<a href="https://vcee.univie.ac.at/home/">Vienna Center for Experimental Economics</a>], [<a href="https://www.univie.ac.at/en/">University of Vienna</a>]</p>
            <p>Office 5.332, Oskar-Morgenstern-Platz 1, 1090 Vienna</p>

            <p>Affiliate Faculty: <a href="https://democracyinstitute.ceu.edu/research/de-and-re-democratization-drd">Democracy Institute</a> and <a href="https://socialmind.ceu.edu/">Social Mind Center</a></p>
            <p>Senior Fellow, <a href="https://www.ihs.ac.at/ru/behavioral-economics/">Institute of Advanced Studies Vienna (Insights Austria)</a></p>

            <p>Here is a link to my <a href="https://www.dropbox.com/scl/fi/2mzcqfzp432sdk7qgl2fx/CV_AMurugesan_latest.pdf?rlkey=jbqvsiqfpeo6meja5vgqxxlt9&dl=0">CV</a></p>
            <p>email: <a href="mailto:murugesana@ceu.edu">murugesana@ceu.edu</a></p>

            <p>Bluesky: <a href="https://bsky.app/profile/anandmurugesan.bsky.social">@anandmurugesan.bsky.social</a></p>
            <p>Twitter (retiring soon): <a href="https://twitter.com/tapasiva">@tapasiva</a></p>
        </header>

        <hr>

        <section class="news-section">
            <h2>News</h2>
            <p>Teaching causal inference methods at the <a href="https://methodsnet.org/summer-school/summer-school-2025/">MethodsNet Summer School with CEU</a> this July - registration open.</p>
            </section>

        <hr>

        <section class="research-section">
            <h2>Research</h2>
            <img src="kite.jpg" alt="Anand Murugesan flying a kite" class="research-image">

            <div class="fields-of-interest">
                 <h3>Fields of Interest</h3>
                 <p>Development | Public Economics | Political Behavior | Experimental Economics</p>
                 </div>


            <div class="current-projects">
                <h3>Current projects</h3>
                <ul>
                    <li>[<a href="https://www.dropbox.com/scl/fi/7nvtk4c54o76kv3fsie5rw/DorschMurugesan_Habsburgs_v2.pdf?rlkey=dnnflk2njihrkl2vjbtbyc3zg&dl=0">From Enlightenment to Cameralism: Tax Morale and Fiscal Capacity as Imperial Legacy</a>], with <a href="https://sites.google.com/view/dorsch/home">Michael Dorsch</a></li>
                    <li>Valuing Democracy, with <a href="https://homepage.univie.ac.at/jean-robert.tyran/index.html">Jean-Robert Tyran</a>
                        <ul>
                            <li>[<a href="https://events.ceu.edu/2025-02-26/brownbag-seminar-why-votes-are-not-sale-evidence-institutional-discontinuity-southern">Why votes are (not) for sale? Evidence from an Institutional Discontinuity in Southern India</a>], with J-R Tyran</li>
                            <li>Fighting Cash-for-Votes: Information Interventions, with J-R Tyran</li>
                            <li>Voters' Dilemma, with Thiagu Ranganathan and J-R Tyran</li>
                        </ul>
                    </li>
                    <li>[<a href="https://homepage.univie.ac.at/jean-robert.tyran/wwtf.html">Measuring democratic resilience: Experimental validation of surveys</a>], with Jean-Robert Tyran</li>
                    <li>[<a href="https://www.dropbox.com/scl/fi/7gsm45u7gix0iy9f4ppc1/Holy_Cow_ECBS_BrownBag_April2024_v3.pdf?rlkey=ts3cko75rkoob75asyaylc3m8&dl=0">Holy Cow! Conflicts, Markets, and Social Costs of Intolerance</a>], with <a href="https://sites.google.com/view/jitendrasingh07">Jitendra Singh</a>
                        <ul>
                            <li>[<a href="https://www.dropbox.com/s/n5nhjf3zn64f80t/Holy_Cow_AEA2022_Poster.pdf?dl=0">Poster presented at the ASSA 2022 annual meeting</a>]</li>
                        </ul>
                    </li>
                    <li>Give or Take: Experimental examination of bribery vs. extortion, with <a href="https://robinnes.weebly.com/">Robert Innes</a></li>
                </ul>
            </div>

            <div class="book-section">
                <h3>Book</h3>
                 <p>[*<a href="https://link.springer.com/book/10.1007/978-981-99-3905-3">Demystifying causal inference</a>*: Public Policy Applications with R] (2023), with Vikram Dayal, Springer <span id="book-accesses">Number of Accesses: >8000 since 1 October 2023</span></p>
                 <script>
                 // Original script provided by user
                 // Note: This script relies on the specific structure of the Springer page
                 // and might break if the external website changes.
                 fetch('https://link.springer.com/book/10.1007/978-981-99-3905-3')
                   .then(response => response.text())
                   .then(html => {
                     const parser = new DOMParser();
                     const doc = parser.parseFromString(html, 'text/html');
                     const accessesElement = doc.querySelector('span.c-article-metrics-bar__value');
                     const accesses = accessesElement ? accessesElement.textContent.trim() : "N/A";
                     document.getElementById('book-accesses').innerText = `Number of Accesses: ${accesses}`;
                   })
                   .catch(err => console.error('Failed to fetch page: ', err));
                 </script>
            </div>

            <div class="publications-section">
                <h3>Publications</h3>
                <ul>
                    <li>["<a href="https://www.sciencedirect.com/science/article/abs/pii/S221480432200088X">Leader and citizens participation for the environment: Experimental evidence from Eastern Europe,</a>"] with Tiziana Centofanti, *Journal of Behavioral and Experimental Economics,* October 2022 [<a href="https://data.mendeley.com/datasets/2ssxp4cj23/1">Replication files on Mendeley Data</a>]</li>
                    <li>["*<a href="https://onlinelibrary.wiley.com/doi/10.1111/rode.12924">Drain on your health</a>*: Sanitation externalities from dirty drains in India,"] with Vikram Dayal and Tauhidur Rahman, *Review of Development Economics,* November 2022 [<a href="https://data.mendeley.com/datasets/2c3kzy4v93/3">Replication files on Mendeley Data</a>]</li>
                    <li>["<a href="https://www.doi.org/10.1017/S1355770X21000152">Air Pollution Trade-Offs in Developing Countries: An Empirical Model of Health Effects in Goa, India,</a>"] with Sanghamitra Das, Vikram Dayal and Uma Rajarathnam, *Environment and Development Economics*, June 2021 [<a href="https://www.dropbox.com/sh/nbfek922paco3vl/AACi31LUrwKxoVm4ugDoyTR5a?dl=0">Replication files</a>]</li>
                    <li>["<a href="https://oxfordre.com/politics/view/10.1093/acrefore/9780190228637.001.0001/acrefore-9780190228637-e-1334">Electoral clientelism and vote buying,</a>"] *Oxford Research Encyclopedia of Politics*, 2020</li>
                    <li>["<a href="https://doi.org/10.1175/WCAS-D-12-00022.1">Use of Weather Information for Agricultural Decision Making,</a>"] with George Frisvold, *Weather, Climate and Society*, 5, January Issue, 55-69, 2013.</li>
                </ul>
            </div>

             <div class="working-papers">
                <h3>Working papers</h3>
                 <ul>
                     <li>["<a href="https://www.dropbox.com/s/c7nslrtg0tg4b77/Markets_for_Children_MurugesanInnes_June2022.pdf?dl=0">Markets For Children</a>*: International Adoptions, IVF, and U.S. Foster Care,"] with Robert Innes (r & r)</li>
                     <li>[<a href="https://www.econstor.eu/bitstream/10419/279254/1/cesifo1_wp10504.pdf">Paying cash for votes</a>] with Jean-Robert Tyran (forthcoming, <a href="https://www.e-elgar.com/shop/gbp/elgar-encyclopedia-of-public-choice-9781802207743.html">Elgar Encyclopedia of Public Choice</a>)</li>
                     <li>Greening the margins: Evidence of amplifying investments in local environmental restoration, with <a href="https://people.ceu.edu/tiziana_centofanti">T. Centofanti</a></li>
                 </ul>
            </div>

             <div class="other-research">
                 <h3>Other</h3>
                 <p>[<a href="https://knowledge4policy.ec.europa.eu/projects-activities/understanding-our-political-nature-how-put-knowledge-reason-heart-political_en">Understanding our Political Nature: How to put knowledge and reason at the heart of political decision-making</a>], author of [<a href="https://www.dropbox.com/s/y3aowk1dxekfzsv/Economics_PoliticalBehavior_JRC_Nov2018.pdf?dl=00">the economics team report</a>] with <a href="https://www.researchgate.net/profile/Martina-Barjakova-2">Martina Barjaková</a> and <a href="https://sites.google.com/view/michael-vlassopoulos/home">Michael Vlassopoulos</a>, 2019 (the report was a foundation for the <a href="https://ec.europa.eu/commission/presscorner/detail/en/ip_20_2250">European Democracy Action Plan</a>)</p>
             </div>

             <div class="presentations-visits">
                 <h4>Recent and upcoming presentations/research visits</h4>
                 <ul>
                     <li>Azim Premji University, Bangalore (August 20, 2024)</li>
                     <li>[<a href="https://slovakecon.sk/seam2024/program.html">Slovak Economic Association Meeting (SEAM 2024)</a>] (September 12 - 13, 2024)</li>
                     <li>[<a href="https://cornell.app.box.com/s/upylx989go5rnnu60mtyu5n8ohz6c8mi">CRADLE, Cornell University</a>] (Oct 3 - 5, 2024)</li>
                     <li>[<a href="https://www.sciencespo.fr/axpo/people/visiting-fellows/">Sciences Po</a>], Paris (Research visit, 10 October - 3 November, 2024)</li>
                     <li>Vienna Behavioral Circle, Wirtschaftsuniversität (15 November 2024)</li>
                     <li>[<a href="http://econdse.org/wp-content/uploads/Programme-Schedule-2.pdf">DSE Winter School 2024</a>] (12 - 14 December)</li>
                     <li>[<a href="https://www.dropbox.com/scl/fi/ekew0xskr4c3zi8zl6fim/BREW-ESA_conference_schedule2024.pdf?rlkey=004e5i4df5xyv9s99q4hpv72r&e=2&st=i8yyxw3v&dl=0">BREW-ESA 2024</a>] (15 - 17 December)</li>
                     <li>[<a href="https://www.isid.ac.in/~acegd/acegd2024/program.html">Annual Conference on Economic Growth and Development 2024</a>], New Delhi (19 - 21 December)</li>
                     <li>[<a href="https://events.ceu.edu/2025-03-31/when-do-citizens-sell-their-votes-evidence-southern-india">Democracy Institute Budapest</a>] Rooftop seminar series (31 March 2025)</li>
                     <li>[<a href="https://epcs2025.sseriga.edu/">European Public Choice Society 2025</a>] (April 3 - 5, 2025)</li>
                 </ul>
             </div>

            <div class="collaborators">
                <h4>Links to recent collaborators</h4>
                 <ul>
                     <li><a href="https://iegindia.org/team/vikram-dayal/">Vikram Dayal</a></li>
                     <li><a href="https://sites.google.com/view/dorsch/home">Michael Dorsch</a></li>
                     <li><a href="https://sites.google.com/view/jitendrasingh07">Jitendra Singh</a></li>
                     <li><a href="https://homepage.univie.ac.at/jean-robert.tyran/index.html">Jean-Robert Tyran</a></li>
                 </ul>
            </div>
        </section>

        <hr>

        <section class="teaching-section">
            <h2>Teaching</h2>
            <div class="ceu-teaching">
                <h3>Central European University, Vienna</h3>
                 <h4>Winter 2025</h4>
                 <ul>
                     <li>[<a href="https://ceu.studyguide.timeedit.net/modules/DOPP5078?type=CORE">Impact Evaluation: Policy Applications with R</a>]</li>
                     <li>[<a href="https://ceu.studyguide.timeedit.net/modules/DOPP5383?type=CORE">Advanced Impact Evaluation</a>]</li>
                     <li>[<a href="https://ceu.studyguide.timeedit.net/modules/DOPP5664?type=CORE">Economic Analysis for Public Policy</a>]</li>
                 </ul>
            </div>

            <div class="recommendation-note">
                <h3>Note on Recommendation Letters for Students</h3>
                <p>I am happy to provide recommendation or support letters for students who <strong>have completed at least one of my elective courses</strong>. This and a weeks notice is a necessary condition. If you would like me to write substantive and informative letters, you'd be better served by performing well in my courses and engaging productively in the class. I only write confidential letters, sent directly to the institution, to ensure my evaluations are candid and objective.</p>
            </div>
        </section>

        <hr>

        <section class="sundry-section">
            <h2>Various and sundry</h2>
            <p>Between December 2023 and February 2024, I was shuttling (actually, riding or pillion-riding a motorbike) across the Tamil Nadu and Kerala border (Palakkad-Pollachi), conducting fieldwork for the Valuing Democracy project. Some stills from the field:</p>

            <div class="image-gallery">
                <figure>
                    <img src="Palakkad_Vengodi_Training.jpeg" alt="Training enumerators in Vengodi, Palakkad">
                    <figcaption>Debriefing and training enumerators at the field office in Vengodi, Palakkad. Our go-to lunch place was Hotel Venkatesh Bhavan -- uses a wood-fired stove for cooking and redolent of Malgudi Days.</figcaption>
                </figure>
                 <figure>
                     <img src="PoliticianInterview_Ramassery.jpeg" alt="Interviewing a politician with Libin in Ramassery">
                     <figcaption>We interviewed scores of politicians: here is one with Libin and a stopover for the famed Ramasseri idli with Sreenivasan Ji. <a href="https://www.thehindu.com/life-and-style/food/ramasseri-idli-a-fusion-of-an-idli-and-a-dosa/article34206074.ece">Is it an idli or a dosa?</a></figcaption>
                 </figure>
                 <figure>
                     <img src="Palakkad_Thenari_TeaShopDiscussion.jpeg" alt="Impomptu discussion at a tea stall in Thenari, Palakkad">
                     <figcaption>An impromptu discussion at a tea stall (with the stall owner, an insightful, white-bearded, old friend of Sreenivasan Ji's father) and the trusted Honda that got us around.</figcaption>
                 </figure>
                 <figure>
                     <img src="Palakkad_Vengodi_Handloom.jpeg" alt="Visit to Khadi cottage industry in Vengodi, Palakkad">
                     <figcaption>An inspiring visit to the <a href="https://www.mkgandhi.org/swadeshi_khadi/whatiskhadi.htm">Khadi</a> cottage industry next door (we bought handmade fabric for made-to-fit shirts by a local tailor) and taking in the moment with a view of the Silent Valley.</figcaption>
                 </figure>
                <figure>
                     <img src="Palakkad_Para_LunchPlace.jpeg" alt="Hotel Venkatesh Bhavan lunch place in Palakkad">
                     </figure>
                 <figure>
                     <img src="Idli_Ramassery.jpeg" alt="Ramassery idli">
                     </figure>
                  <figure>
                     <img src="Pollachi_Thimmanguthu.png" alt="Motorbike used for fieldwork in Pollachi">
                      </figure>
                 <figure>
                     <img src="Palakkad_SilentValley_Trees.jpeg" alt="View of Silent Valley">
                     </figure>

            </div>
            <p>Here is my sketch (below) of a bestselling book my daughter recommended I read, and I recommend you do; [<a href="https://www.charliemackesy.com/">it's a short read</a>].</p>
            <img src="theboythemule.png" alt="Sketch of The Boy, the Mole, the Fox and the Horse" class="book-sketch">

            <p>And a dated picture of traditional seed sowing on my parents' farm in Tamil Nadu, India (below, on the left) and me breaking traditions (on the right).</p>
            <div class="farm-images">
                <img src="6979F656-02F0-472E-84A1-AB3B22C5BCAB.jpeg" alt="Traditional seed sowing on a farm">
                <img src="till.jpeg" alt="Anand Murugesan on a tractor tilling a field">
            </div>


            <p>My brother worked on [<a href="https://academic.oup.com/mnras/article/483/2/2398/5222687">the effect of angular momentum or spin velocity in the formation of galaxies</a>]; more recently on examining [<a href="https://arxiv.org/pdf/2006.08103.pdf">the interactive effect of angular momentum and gravitation</a>] in the formation of celestial bodies. My brother lives in the part of the world where, in theory, water flowing down the drain is expected to spin in the opposite direction compared to the drains in parts I am in... ;)</p>

            <div class="food-places">
                <p>Shoutout to places I love eating at:</p>
                <ul>
                    <li>Dosa at [<a href="https://maps.app.goo.gl/ziETrgusZctJkbQFA">SN Refreshments</a>]</li>
                    <li>South Indian filter coffee at [<a href="https://aabsweets.com/">A2B</a>] with [<a href="https://www.malgudidays.com.au/blogs/news/chicory-and-south-indian-filter-coffee">chicory</a>] in the mix (as in the New Orleans-style [<a href="https://shop.cafedumonde.com/coffee/">Cafe du Monde</a>])</li>
                    <li>Pizza at [<a href="https://maps.app.goo.gl/Gnx1d4ax8pvLoVx79">Doma</a>]</li>
                    <li>Gelato at [<a href="https://maps.app.goo.gl/T8giLPcs9ZqubqCJ7">Carapina</a>] (two doors down from Doma -- an incredibly delightful corner)</li>
                    <li>Phad krapow at [<a href="https://maps.app.goo.gl/UCSbstNjs5gy8T7w9">Kamala Thai Imbiss</a>]</li>
                    <li>Sacher torta at [<a href="http://googlecarbon.com/maps.google.com/5">Hotel Sacher</a>]</li>
                </ul>
            </div>

            <div class="food-places-return">
                 <p>And where I'd be happy to go back:</p>
                 <ul>
                     <li>[<a href="https://guide.michelin.com/at/en/ile-de-france/paris/restaurant/kwon">Kwon</a>] and [<a href="https://www.kodawari-ramen.com/kodawari-tsukiji-la-carte/">Kodawari Tsukiji</a>], Paris</li>
                     <li>[<a href="https://www.rasikarestaurant.com/">Rasika</a>], DC and [<a href="https://www.semma.nyc/">Semma</a>], NYC</li>
                 </ul>
            </div>

            <link rel="stylesheet" href="https://embedbsky.com/embedbsky.com-master-min.css" />
            <div id="embedbsky-com-timeline-embed"></div>
            <script>
                // Original Bluesky embed script
                // Note: This relies on an external script and service.
                let containerWidth=400,containerHeight=400;const getHtml=async t=>{const e=await fetch(t);return 200!==e.status?'<p><strong>No feed data could be located</p></strong>':e.text()};document.addEventListener('DOMContentLoaded',(async()=>{const t=(new Date).toISOString(),e=document.getElementById('embedbsky-com-timeline-embed');e.style.width=`${containerWidth}px`,e.style.height=`${containerHeight}px`;const n=await getHtml(`https://embedbsky.com/feeds/5fba2aa9a3fe9f7fc7706e06e97c0e168ece11ea03482ff583f41f56732c2c30.html?v=${t}`);e.innerHTML=n}));
            </script>
            </section>

        <hr>

        <footer>
            <p class="quote">"The first principle is that you must not fool yourself -- and you are the easiest person to fool. So you have to be very careful about that. After you've not fooled yourself, it's easy not to fool other scientists. You just have to be honest in a conventional way after that." - Richard Feynman at Caltech, 1974</p>

            <p class="small-text">Photo credit: Me flying a kite (Sabya); Fieldwork in Palakkad (Sreenivasan ji, Libin or me)</p>

             <script async src="https://www.googletagmanager.com/gtag/js?id=UA-162382665-1"></script>
            <script>
              window.dataLayer = window.dataLayer || [];
              function gtag(){dataLayer.push(arguments);}
              gtag('js', new Date());
              gtag('config', 'UA-162382665-1');
            </script>
        </footer>

    </div> </body>
</html>

<!-- 
*Associate Professor of Economics* <br/> 
[Department of Public Policy](https://people.ceu.edu/anand_murugesan), [Central European University, Vienna](https://www.ceu.edu/vienna)<br/>
B-412, Quellenstraße 51, 1100 Vienna <br/>
Phone: +43.1.25230.2054

*Senior Researcher* <br/>
[Vienna Center for Experimental Economics](https://vcee.univie.ac.at/home/), [University of Vienna](https://www.univie.ac.at/en/) <br/>
Office 5.332, Oskar-Morgenstern-Platz 1, 1090 Vienna <br/>

Affiliate Faculty: [Democracy Institute](https://democracyinstitute.ceu.edu/research/de-and-re-democratization-drd) and [Social Mind Center](https://socialmind.ceu.edu/)

Senior Fellow, [Institute of Advanced Studies Vienna (Insights Austria)](https://www.ihs.ac.at/ru/behavioral-economics/)

Here is a link to my [CV](https://www.dropbox.com/scl/fi/2mzcqfzp432sdk7qgl2fx/CV_AMurugesan_latest.pdf?rlkey=jbqvsiqfpeo6meja5vgqxxlt9&dl=0)

email: <murugesana@ceu.edu>

Bluesky: [@anandmurugesan.bsky.social](https://bsky.app/profile/anandmurugesan.bsky.social)

Twitter (retiring soon): [@tapasiva](https://twitter.com/tapasiva)

---
## News

Teaching causal inference methods at the [MethodsNet Summer School with CEU](https://methodsnet.org/summer-school/summer-school-2025/) this July - registration open.

<!-- [CEU Assistant Professor opening](https://careers.ceu.edu/job/Vienna-Assistant-Professor-%28fmd%29-1100/1138728155/) for scholars applying NLP and related methods to analyze public policy topics -- inviting applications!

 [Starting June 2024, I'll work part-time at the University of Vienna to research "Emotional Politics of Democracies" with Jean-Robert Tyran, funded by a Horizon Europe grant](http://encodemotions.eu/). 

[*Demystifying causal inference*](https://link.springer.com/book/10.1007/978-981-99-3905-3) [(availabe on Amazon)](https://www.amazon.com/Demystifying-Causal-Inference-Public-applications/dp/9819939046/ref=monarch_sidesheet)-->

---

## Research 
<img src="kite.jpg" width="495" height="330" /> 

**Fields of Interest**

Development  | Public Economics

Political Behavior | Experimental Economics 
 
### Current projects 

[From Enlightenment to Cameralism: Tax Morale and Fiscal Capacity as Imperial Legacy](https://www.dropbox.com/scl/fi/7nvtk4zox76kv3fsie5rw/DorschMurugesan_Habsburgs_v2.pdf?rlkey=dnnflk2njihrkl2vjbtbyc3zg&dl=0), with [Michael Dorsch](https://sites.google.com/view/dorsch/home)

Valuing Democracy, with [Jean-Robert Tyran](https://homepage.univie.ac.at/jean-robert.tyran/index.html)

  - [Why votes are (not) for sale? Evidence from an Institutional Discontinuity in Southern India](https://events.ceu.edu/2025-02-26/brownbag-seminar-why-votes-are-not-sale-evidence-institutional-discontinuity-southern), with J-R Tyran
  - Fighting Cash-for-Votes: Information Interventions, with J-R Tyran
  - Voters' Dilemma, with Thiagu Ranganathan and J-R Tyran

[Measuring democratic resilience: Experimental validation of surveys](https://homepage.univie.ac.at/jean-robert.tyran/wwtf.html), with Jean-Robert Tyran
<!--  Emotions in Politics, with [Jorg Matthes](https://advertisingresearch.univie.ac.at/team/joerg-matthes/), Ruta Kaskeleviciute and Jean-Robert Tyran -->

[Holy Cow! Conflicts, Markets, and Social Costs of Intolerance](https://www.dropbox.com/scl/fi/7gsm45u7gix0iy9f4ppc1/Holy_Cow_ECBS_BrownBag_April2024_v3.pdf?rlkey=ts3cko75rkoob75asyaylc3m8&dl=0), with [Jitendra Singh](https://sites.google.com/view/jitendrasingh07)
  - [Poster presented at the ASSA 2022 annual meeting](https://www.dropbox.com/s/n5nhjf3zn64f80t/Holy_Cow_AEA2022_Poster.pdf?dl=0)

Give or Take: Experimental examination of bribery vs. extortion, with [Robert Innes](https://robinnes.weebly.com/)

<!-- [Let them play games! Experimental methods to elicit social norms](https://www.dropbox.com/s/frysh7muu82q56q/LetThemPlayGames_ESABologna2022_Abstract.pdf?dl=0), with Mahendran Chokkalingam, Christophe Heintz and Mia Karabegovic
The sticky self and the icky other!* Using coordination games to elicit self-image signals with C. Heintz and M. Karabegovic
Comparing the response variance between the many-to-one and one-to-one norm elicitation method 
Impact of the US opioid crisis on Children, with Dana Andersen -->

### Book 
<script>
fetch('https://link.springer.com/book/10.1007/978-981-99-3905-3')
  .then(response => response.text())
  .then(html => {
    const parser = new DOMParser();
    const doc = parser.parseFromString(html, 'text/html');

    // Extract the exact number using the correct CSS selector
    const accessesElement = doc.querySelector('span.c-article-metrics-bar__value'); 
    const accesses = accessesElement ? accessesElement.textContent.trim() : "N/A";

    document.getElementById('book-accesses').innerText = `Number of Accesses: ${accesses}`;
  })
  .catch(err => console.error('Failed to fetch page: ', err));
</script>

[*Demystifying causal inference*: Public Policy Applications with R](https://link.springer.com/book/10.1007/978-981-99-3905-3) (2023), with Vikram Dayal, Springer [Number of Accesses: >8000 since 1 October 2023]

### Publications 
["Leader and citizens participation for the environment: Experimental evidence from Eastern Europe,"](https://www.sciencedirect.com/science/article/abs/pii/S221480432200088X) with Tiziana Centofanti, *Journal of Behavioral and Experimental Economics,* October 2022 [Replication files on Mendeley Data](https://data.mendeley.com/datasets/2ssxp4cj23/1)

["*Drain on your health*: Sanitation externalities from dirty drains in India,"](https://onlinelibrary.wiley.com/doi/10.1111/rode.12924) with Vikram Dayal and Tauhidur Rahman, *Review of Development Economics,* November 2022 [Replication files on Mendeley Data](https://data.mendeley.com/datasets/2c3kzy4v93/3)

["Air Pollution Trade-Offs in Developing Countries: An Empirical Model of Health Effects in Goa, India,"](https://www.doi.org/10.1017/S1355770X21000152) with Sanghamitra Das, Vikram Dayal and Uma Rajarathnam, *Environment and Development Economics*, June 2021
[Replication files](https://www.dropbox.com/sh/nbfek922paco3vl/AACi31LUrwKxoVm4ugDoyTR5a?dl=0)

["Electoral clientelism and vote buying,"](https://oxfordre.com/politics/view/10.1093/acrefore/9780190228637.001.0001/acrefore-9780190228637-e-1334) *Oxford Research Encyclopedia of Politics*, 2020

["Use of Weather Information for Agricultural Decision Making,"](https://doi.org/10.1175/WCAS-D-12-00022.1) with George Frisvold, *Weather, Climate and Society*, 5, January Issue, 55-69, 2013.

### Working papers

["*Markets For Children*: International Adoptions, IVF, and U.S. Foster Care,"](https://www.dropbox.com/s/c7nslrtg0tg4b77/Markets_for_Children_MurugesanInnes_June2022.pdf?dl=0) with Robert Innes (r & r)

[Paying cash for votes](https://www.econstor.eu/bitstream/10419/279254/1/cesifo1_wp10504.pdf) with Jean-Robert Tyran (forthcoming, [Elgar Encyclopedia of Public Choice](https://www.e-elgar.com/shop/gbp/elgar-encyclopedia-of-public-choice-9781802207743.html))

Greening the margins: Evidence of amplifying investments in local environmental restoration, with [T. Centofanti](https://people.ceu.edu/tiziana_centofanti)

<!-- ["Demystifying causal inference: ingredients of a recipe,"](https://www.dropbox.com/s/13fxlc6asavwdaf/demystifycausalinference_ieg_wp393.pdf?dl=0) with Vikram Dayal, *IEG working paper* -->

### Other

[Understanding our Political Nature: How to put knowledge and reason at the heart of political decision-making](https://knowledge4policy.ec.europa.eu/projects-activities/understanding-our-political-nature-how-put-knowledge-reason-heart-political_en), author of [the economics team report](https://www.dropbox.com/s/y3aowk1dxekfzsv/Economics_PoliticalBehavior_JRC_Nov2018.pdf?dl=00) with [Martina Barjaková](https://www.researchgate.net/profile/Martina-Barjakova-2) and [Michael Vlassopoulos](https://sites.google.com/view/michael-vlassopoulos/home), 2019 (the report was a foundation for the [European Democracy Action Plan](https://ec.europa.eu/commission/presscorner/detail/en/ip_20_2250))


#### Recent and upcoming presentations/research visits

<!-- [Wirtschafts Universität Wien](https://www.wu.ac.at/en/ims/news/seminar-series/) seminar series (October 11, 2022)

[Università Bocconi](http://www.igier.unibocconi.it/) (November 14 - 18, 2022)

[European Public Choice Society 2023](https://www.epcs2023.uni-hannover.de/en/) (March 22 - 25, 2023)

[Institute of Advanced Studies](https://www.ihs.ac.at/ru/behavioral-economics/) (May 3, 2023)

[Vienna Applied Micro Economics Workshop](https://viennappliedmicroeconomics.weebly.com/workshop.html) (June 19, 2023) 

[Western Economic Association 2023](https://weai.org/conferences/view/13/98th-Annual-Conference) (July 3 - 7, 2023)

[Stanford University](https://kingcenter.stanford.edu/) (July 10 - 12, 2023)

[Center for Development Studies, India](https://cds.edu/#m-10-2022) (August 4, 2023)

[Delhi School of Economics, India](http://econdse.org/cde-seminars/) (August 31, 2023)

[Indian Statistical Institute, Delhi](https://www.isid.ac.in/) (September 1, 2023)

[Democracy Institute Budapest](https://democracyinstitute.ceu.edu/news-events-events/rooftop-seminar-series) Rooftop seminar series (October 2, 2023) 

[Annual Conference on Economic Growth and Development](https://www.isid.ac.in/~acegd/acegd2023/index.html) (18 - 20 December, 2023) 

[Workshop on "Uncovering the Historical Mechanisms of Persistence](https://dpp.ceu.edu/workshop-historical-persistence) (18 - 19 January, 2024)

[Econ CAKE talk, University of Utah](https://economics.utah.edu/events/index.php?trumbaEmbed=view%3Devent%26eventid%3D171610971) (February 23, 2024)

Workshop on Experiments in Research and for Policymaking, EUBA Bratislava (March 21, 2024)

[European Public Choice Society Meeting](https://www.wu.ac.at/epcs2024/) (April 2 - 5, 2024)
-->
Azim Premji University, Bangalore (August 20, 2024)

[Slovak Economic Association Meeting (SEAM 2024)](https://slovakecon.sk/seam2024/program.html) (September 12 - 13, 2024)

[CRADLE, Cornell University](https://cornell.app.box.com/s/upylx989go5rnnu60mtyu5n8ohz6c8mi) (Oct 3 - 5, 2024)

[Sciences Po](https://www.sciencespo.fr/axpo/people/visiting-fellows/), Paris (Research visit, 10 October - 3 November, 2024)

Vienna Behavioral Circle, Wirtschaftsuniversität (15 November 2024)

[DSE Winter School 2024](http://econdse.org/wp-content/uploads/Programme-Schedule-2.pdf) (12 - 14 December)

[BREW-ESA 2024](https://www.dropbox.com/scl/fi/ekew0xskr4c3zi8zl6fim/BREW-ESA_conference_schedule2024.pdf?rlkey=004e5i4df5xyv9s99q4hpv72r&e=2&st=i8yyxw3v&dl=0) (15 - 17 December)

[Annual Conference on Economic Growth and Development 2024](https://www.isid.ac.in/~acegd/acegd2024/program.html), New Delhi (19 - 21 December)

[Democracy Institute Budapest](https://events.ceu.edu/2025-03-31/when-do-citizens-sell-their-votes-evidence-southern-india) Rooftop seminar series (31 March 2025)

[European Public Choice Society 2025](https://epcs2025.sseriga.edu/) (April 3 - 5, 2025)



#### Links to recent collaborators

[Vikram Dayal](https://iegindia.org/team/vikram-dayal/) | [Michael Dorsch](https://sites.google.com/view/dorsch/home) | 
[Jitendra Singh](https://sites.google.com/view/jitendrasingh07) | [Jean-Robert Tyran](https://homepage.univie.ac.at/jean-robert.tyran/index.html)  

## Teaching

### Central European University, Vienna 


**Winter 2025** 

[Impact Evaluation: Policy Applications with R](https://ceu.studyguide.timeedit.net/modules/DOPP5078?type=CORE)

[Advanced Impact Evaluation](https://ceu.studyguide.timeedit.net/modules/DOPP5383?type=CORE)

[Economic Analysis for Public Policy](https://ceu.studyguide.timeedit.net/modules/DOPP5664?type=CORE)

**Note on Recommendation Letters for Students**

I am happy to provide recommendation or support letters for students who **have completed at least one of my elective courses**. This and a weeks notice is a necessary condition. If you would like me to write substantive and informative letters, you'd be better served by performing well in my courses and engaging productively in the class. I only write confidential letters, sent directly to the institution, to ensure my evaluations are candid and objective.

## Bio

PhD, University of Maryland, College Park <br/>
 [Economics of Society: Essays on Health, Marriage, and Child Adoption]<br/>
MA, Jawaharlal Nehru University, New Delhi<br/>
BCom, Bangalore University (St. Joseph's College)<br/>

Born 1980, Bangalore, Indian citizenship

## Various and sundry

Between December 2023 and February 2024, I was shuttling (actually, riding or pillion-riding a motorbike) across the Tamil Nadu and Kerala border (Palakkad-Pollachi), conducting fieldwork for the Valuing Democracy project. Some stills from the field: 

<img src="Palakkad_Vengodi_Training.jpeg" width="225" height="150" /> <img src="Palakkad_Para_LunchPlace.jpeg" width="225" height="150" /> 

Debriefing and training enumerators at the field office in Vengodi, Palakkad. Our go-to lunch place was Hotel Venkatesh Bhavan -- uses a wood-fired stove for cooking and redolent of [Malgudi Days](https://www.youtube.com/watch?v=mIYA5qANs_A).

<img src="PoliticianInterview_Ramassery.jpeg" width="225" height="150" /> <img src="Idli_Ramassery.jpeg" width="225" height="150" /> 

We interviewed scores of politicians: here is one with Libin and a stopover for the famed Ramasseri idli with Sreenivasan Ji. [Is it an idli or a dosa?](https://www.thehindu.com/life-and-style/food/ramasseri-idli-a-fusion-of-an-idli-and-a-dosa/article34206074.ece)

<img src="Palakkad_Thenari_TeaShopDiscussion.jpeg" width="225" height="150" /> <img src="Pollachi_Thimmanguthu.png" width="225" height="150" /> 

An impromptu discussion at a tea stall (with the stall owner, an insightful, white-bearded, old friend of Sreenivasan Ji's father) and the trusted Honda that got us around. 

<img src="Palakkad_Vengodi_Handloom.jpeg" width="225" height="150" /> <img src="Palakkad_SilentValley_Trees.jpeg" width="225" height="150" /> 

An inspiring visit to the [Khadi](https://www.mkgandhi.org/swadeshi_khadi/whatiskhadi.htm) cottage industry next door (we bought handmade fabric for made-to-fit shirts by a local tailor) and taking in the moment with a view of the Silent Valley. 



<!-- You can find fieldwork pictures on our [Greening the Margin project here](https://tizianacentofanti.wixsite.com/personalwebsite/gallery) and --> 

Here is my sketch (below) of a bestselling book my daughter recommended I read, and I recommend you do; [it's a short read](https://www.charliemackesy.com/). 

<img src="theboythemule.png" width="150" height="200" /> 

And a dated picture of traditional seed sowing on my parents' farm in Tamil Nadu, India (below, on the left) and me breaking traditions (on the right).

<img src="6979F656-02F0-472E-84A1-AB3B22C5BCAB.jpeg" width="225" height="150" /> <img src="till.jpeg" width="225" height="150" /> 

My brother worked on [the effect of angular momentum or spin velocity in the formation of galaxies](https://academic.oup.com/mnras/article/483/2/2398/5222687); more recently on examining [the interactive effect of angular momentum and gravitation](https://arxiv.org/pdf/2006.08103.pdf) in the formation of celestial bodies. My brother lives in the part of the world where, in theory, water flowing down the drain is expected to spin in the opposite direction compared to the drains in parts I am in... ;) <br/>

Shoutout to places I love eating at:  
- Dosa at [SN Refreshments](https://maps.app.goo.gl/ziETrgusZctJkbQFA)
- South Indian filter coffee at [A2B](https://aabsweets.com/) with [chicory](https://www.malgudidays.com.au/blogs/news/chicory-and-south-indian-filter-coffee) in the mix (as in the New Orleans-style [Cafe du Monde](https://shop.cafedumonde.com/coffee/))
- Pizza at [Doma](https://maps.app.goo.gl/Gnx1d4ax8pvLoVx79)
- Gelato at [Carapina](https://maps.app.goo.gl/T8giLPcs9ZqubqCJ7) (two doors down from Doma -- an incredibly delightful corner)
- Phad krapow at [Kamala Thai Imbiss](https://maps.app.goo.gl/UCSbstNjs5gy8T7w9)
- Sacher torta at [Hotel Sacher](https://maps.app.goo.gl/Ca3dWBSgW5Q4E5Rf9)

And where I'd be happy to go back: 
- [Kwon](https://guide.michelin.com/at/en/ile-de-france/paris/restaurant/kwon) and [Kodawari Tsukiji](https://www.kodawari-ramen.com/kodawari-tsukiji-la-carte/), Paris
- [Rasika](https://www.rasikarestaurant.com/), DC and [Semma](https://www.semma.nyc/), NYC

<link rel="stylesheet" href="https://embedbsky.com/embedbsky.com-master-min.css" /><div id="embedbsky-com-timeline-embed"></div><script>let containerWidth=400,containerHeight=400;const getHtml=async t=>{const e=await fetch(t);return 200!==e.status?'<p><strong>No feed data could be located</p></strong>':e.text()};document.addEventListener('DOMContentLoaded',(async()=>{const t=(new Date).toISOString(),e=document.getElementById('embedbsky-com-timeline-embed');e.style.width=`${containerWidth}px`,e.style.height=`${containerHeight}px`;const n=await getHtml(`https://embedbsky.com/feeds/5fba2aa9a3fe9f7fc7706e06e97c0e168ece11ea03482ff583f41f56732c2c30.html?v=${t}`);e.innerHTML=n}));</script>

<!-- 
<a class="twitter-timeline" href="https://twitter.com/tapasiva?ref_src=twsrc%5Etfw">Tweets by tapasiva</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<script src="https://static.elfsight.com/platform/platform.js" async></script>
<div class="elfsight-app-47c64d34-7e71-4312-8875-c432c26785cf" data-elfsight-app-lazy></div>
-->
---
*"The first principle is that you must not fool yourself -- and you are the easiest person to fool. So you have to be very careful about that. After you've not fooled yourself, it's easy not to fool other scientists. You just have to be honest in a conventional way after that." - Richard Feynman at Caltech, 1974*

<p style="font-size: x-small;"> <!--  Excerpt from my 2015 Research Statement, which continues to hold today (I've mixed feelings about this consistency): `` ...The underlying theme of my research is throwing light on issues of society, where individual interest and a larger collective bargain are divergent ...and seeing how institutional arrangements, legal or economic, can improve individual incentives for better collective outcomes..."-->
  
Photo credit: Me flying a kite (Sabya); Fieldwork in Palakkad (Sreenivasan ji, Libin or me)
</p>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-162382665-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-162382665-1');
</script>
 

-->



