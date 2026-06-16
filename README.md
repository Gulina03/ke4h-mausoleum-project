<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mausoleum of Khoja Ahmed Yasawi | KE4H Project</title>

<style>
* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: Georgia, 'Times New Roman', serif;
    background: #17150f;
    color: #f4efe3;
    line-height: 1.7;
}

nav {
    position: sticky;
    top: 0;
    z-index: 1000;
    background: rgba(23, 21, 15, 0.95);
    border-bottom: 1px solid rgba(212, 181, 118, 0.4);
    padding: 14px 30px;
    text-align: center;
}

nav a {
    color: #d4b576;
    text-decoration: none;
    margin: 0 12px;
    font-size: 14px;
    letter-spacing: 1px;
}

nav a:hover {
    color: #ffffff;
}

.hero {
    min-height: 100vh;
    background:
        linear-gradient(rgba(10,10,10,0.45), rgba(10,10,10,0.8)),
        url("https://commons.wikimedia.org/wiki/Special:FilePath/Mausoleum%20of%20Khoja%20Ahmed%20Yasawi%20in%20Hazrat-e%20Turkestan%2C%20Kazakhstan.jpg");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 60px;
}

.hero-box {
    max-width: 760px;
    background: rgba(20, 18, 13, 0.78);
    border: 1px solid rgba(212, 181, 118, 0.55);
    border-radius: 28px;
    padding: 45px;
}

.hero h1 {
    font-size: 58px;
    line-height: 1.05;
    margin: 0 0 20px;
    color: #f8e7b8;
}

.hero p {
    font-size: 20px;
    color: #eee2c8;
}

section {
    padding: 80px 9%;
}

.section-title {
    font-size: 42px;
    color: #d4b576;
    margin-bottom: 30px;
    border-bottom: 1px solid rgba(212,181,118,0.4);
    padding-bottom: 12px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 28px;
}

.card {
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid rgba(212,181,118,0.35);
    border-radius: 24px;
    padding: 28px;
    backdrop-filter: blur(3px);
}

.card h3 {
    color: #f4d58d;
    margin-top: 0;
}

.photo-card {
    min-height: 360px;
    border-radius: 24px;
    background-size: cover;
    background-position: center;
    border: 1px solid rgba(212,181,118,0.35);
}

.bg-one {
    background-image:
        linear-gradient(rgba(0,0,0,0.15), rgba(0,0,0,0.45)),
        url("https://commons.wikimedia.org/wiki/Special:FilePath/Mausoleum%20of%20Khoja%20Ahmed%20Yasawi.jpg");
}

.bg-two {
    background-image:
        linear-gradient(rgba(0,0,0,0.15), rgba(0,0,0,0.45)),
        url("https://commons.wikimedia.org/wiki/Special:FilePath/Mausoleum%20of%20Khoja%20Ahmed%20Yasawi%2010.jpg");
}

.bg-three {
    background-image:
        linear-gradient(rgba(0,0,0,0.20), rgba(0,0,0,0.50)),
        url("https://commons.wikimedia.org/wiki/Special:FilePath/Mausoleum%20of%20Khoja%20Ahmed%20Yasavi%20in%20Turkestan%2C%20Kazakhstan.jpg");
}

ul, ol {
    padding-left: 22px;
}

li {
    margin-bottom: 10px;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 18px;
    background: rgba(255,255,255,0.05);
}

th, td {
    border: 1px solid rgba(212,181,118,0.35);
    padding: 14px;
    vertical-align: top;
}

th {
    background: rgba(212,181,118,0.18);
    color: #f6dc9c;
}

pre {
    background: #0f0e0a;
    color: #f4efe3;
    padding: 22px;
    border-radius: 18px;
    overflow-x: auto;
    border: 1px solid rgba(212,181,118,0.35);
}

.query-box {
    margin-bottom: 28px;
}

.tag {
    display: inline-block;
    padding: 6px 12px;
    border: 1px solid rgba(212,181,118,0.55);
    border-radius: 30px;
    color: #f4d58d;
    margin: 4px 6px 4px 0;
    font-size: 13px;
}

.highlight {
    color: #f4d58d;
    font-weight: bold;
}

.footer {
    text-align: center;
    padding: 60px 20px;
    background:
        linear-gradient(rgba(10,10,10,0.65), rgba(10,10,10,0.9)),
        url("https://commons.wikimedia.org/wiki/Special:FilePath/Mausoleum%20of%20Khoja%20Ahmed%20Yasawi%20in%20Hazrat-e%20Turkestan%2C%20Kazakhstan.jpg");
    background-size: cover;
    background-position: center;
}

.footer h2 {
    font-size: 52px;
    color: #f8e7b8;
}

@media (max-width: 800px) {
    .hero {
        padding: 30px;
    }

    .hero h1 {
        font-size: 40px;
    }

    .grid {
        grid-template-columns: 1fr;
    }

    nav a {
        display: inline-block;
        margin: 6px;
    }
}
</style>
</head>

<body>

<nav>
    <a href="#overview">Overview</a>
    <a href="#rq">Research Questions</a>
    <a href="#sparql">SPARQL</a>
    <a href="#gaps">Gaps</a>
    <a href="#llm">LLMs</a>
    <a href="#rdf">RDF</a>
    <a href="#challenges">Challenges</a>
    <a href="#conclusion">Conclusion</a>
</nav>

<header class="hero">
    <div class="hero-box">
        <h1>Mausoleum of Khoja Ahmed Yasawi</h1>
        <p>
            Knowledge Graph Enrichment using Wikidata, SPARQL and Large Language Models
        </p>
        <p>
            KE4H Project — Knowledge Engineering for the Humanities
        </p>
        <p>
            <span class="tag">Wikidata</span>
            <span class="tag">SPARQL</span>
            <span class="tag">LLMs</span>
            <span class="tag">RDF Triples</span>
            <span class="tag">Cultural Heritage</span>
        </p>
    </div>
</header>

<section id="overview">
    <h2 class="section-title">Project Overview</h2>

    <div class="grid">
        <div class="card">
            <h3>Topic</h3>
            <p>
                This project focuses on the <span class="highlight">Mausoleum of Khoja Ahmed Yasawi</span>,
                a major cultural and religious monument located in Turkistan, Kazakhstan.
            </p>
            <p>
                The project investigates how this monument is represented in Wikidata and how its
                knowledge graph representation can be enriched with additional cultural and religious information.
            </p>
        </div>

        <div class="photo-card bg-one"></div>
    </div>

    <div class="grid" style="margin-top:28px;">
        <div class="card">
            <h3>Wikidata Entity</h3>
            <p>
                The selected entity in Wikidata is:
            </p>
            <p>
                <strong>Mausoleum of Khoja Ahmed Yasawi</strong><br>
                Wikidata ID: <strong>Q46069</strong>
            </p>
            <p>
                Wikidata already contains factual information such as country, location,
                architectural style, heritage designation, and historical metadata.
            </p>
        </div>

        <div class="card">
            <h3>Project Goal</h3>
            <p>
                The goal is to identify missing or underrepresented knowledge and propose new RDF triples
                that could enrich the knowledge graph.
            </p>
            <p>
                The enrichment process combines:
            </p>
            <ul>
                <li>SPARQL exploration of Wikidata</li>
                <li>Knowledge gap identification</li>
                <li>LLM-based generation using ChatGPT and Gemini</li>
                <li>Human validation of RDF triples</li>
            </ul>
        </div>
    </div>
</section>

<section id="rq">
    <h2 class="section-title">Research Questions</h2>

    <div class="card">
        <h3>Main Research Question</h3>
        <p>
            <strong>
            What cultural, religious, and historical information about the Mausoleum of Khoja Ahmed Yasawi
            is missing from Wikidata, and how can it be added using Large Language Models?
            </strong>
        </p>
    </div>

    <div class="grid" style="margin-top:28px;">
        <div class="card">
            <h3>RQ1</h3>
            <p>
                What information about the Mausoleum of Khoja Ahmed Yasawi is already represented in Wikidata?
            </p>
        </div>

        <div class="card">
            <h3>RQ2</h3>
            <p>
                Which cultural, religious, and semantic aspects are missing or underrepresented?
            </p>
        </div>

        <div class="card">
            <h3>RQ3</h3>
            <p>
                How can ChatGPT and Gemini support the creation of new RDF triples for knowledge graph enrichment?
            </p>
        </div>

        <div class="card">
            <h3>RQ4</h3>
            <p>
                Which LLM produces outputs that are more useful for targeted RDF enrichment?
            </p>
        </div>
    </div>
</section>

<section id="sparql">
    <h2 class="section-title">SPARQL Queries</h2>

    <p>
        We used SPARQL queries to explore the existing information in Wikidata and to verify
        whether specific cultural and religious information was already represented.
    </p>

    <div class="query-box card">
        <h3>Query 1 — Basic Exploration Query</h3>
        <p>
            This query retrieved the main properties and values associated with the Mausoleum of Khoja Ahmed Yasawi.
        </p>
        <p>
            <strong>Result:</strong> Wikidata contains factual metadata such as Kazakhstan, Turkistan,
            Timurid architecture, World Heritage Site status, Timur, and construction date.
        </p>
        <pre>
SELECT ?propertyLabel ?valueLabel
WHERE {
  wd:Q46069 ?p ?value .
  ?property wikibase:directClaim ?p .

  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?property rdfs:label ?propertyLabel .
    ?value rdfs:label ?valueLabel .
  }
}
LIMIT 50
        </pre>
    </div>

    <div class="query-box card">
        <h3>Query 2 — DISTINCT Query</h3>
        <p>
            This query retrieved unique heritage designations associated with the mausoleum.
        </p>
        <p>
            <strong>Purpose:</strong> To avoid duplicate results and confirm the UNESCO World Heritage status.
        </p>
        <pre>
SELECT DISTINCT ?heritageLabel
WHERE {
  wd:Q46069 wdt:P1435 ?heritage .
  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?heritage rdfs:label ?heritageLabel .
  }
}
        </pre>
    </div>

    <div class="query-box card">
        <h3>Query 3 — OPTIONAL Query</h3>
        <p>
            This query checked whether architect information was available in Wikidata.
        </p>
        <p>
            <strong>Result:</strong> No architect was returned, indicating that this information is missing
            or not explicitly represented.
        </p>
        <pre>
SELECT ?itemLabel ?architectLabel
WHERE {
  VALUES ?item { wd:Q46069 }

  OPTIONAL { ?item wdt:P84 ?architect . }

  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
  }
}
        </pre>
    </div>

    <div class="query-box card">
        <h3>Query 4 — FILTER Query</h3>
        <p>
            This query filtered out image-related information and focused on relevant descriptive properties.
        </p>
        <pre>
SELECT ?propertyLabel ?valueLabel
WHERE {
  wd:Q46069 ?p ?value .
  ?property wikibase:directClaim ?p .

  FILTER(?property != wd:P18)

  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?property rdfs:label ?propertyLabel .
    ?value rdfs:label ?valueLabel .
  }
}
LIMIT 20
        </pre>
    </div>

    <div class="query-box card">
        <h3>Query 5 — ORDER BY + LIMIT Query</h3>
        <p>
            This query organized the metadata alphabetically and limited the result to 15 rows.
        </p>
        <p>
            <strong>Result:</strong> The output included World Heritage Site ID, World Heritage criteria,
            TDV Encyclopedia of Islam ID, Commons category, and other metadata.
        </p>
        <pre>
SELECT ?propertyLabel ?valueLabel
WHERE {
  wd:Q46069 ?p ?value .
  ?property wikibase:directClaim ?p .

  SERVICE wikibase:label {
    bd:serviceParam wikibase:language "en".
    ?property rdfs:label ?propertyLabel .
    ?value rdfs:label ?valueLabel .
  }
}
ORDER BY ?propertyLabel
LIMIT 15
        </pre>
    </div>
</section>

<section id="gaps">
    <h2 class="section-title">Knowledge Gaps</h2>

    <div class="grid">
        <div class="card">
            <h3>Gap 1 — Connection with Yasawiyya Sufi Order</h3>
            <p>
                Wikidata does not explicitly represent the connection between the mausoleum and the Yasawiyya Sufi tradition.
            </p>
        </div>

        <div class="card">
            <h3>Gap 2 — Role as a Pilgrimage Site</h3>
            <p>
                The mausoleum is culturally understood as a pilgrimage destination, but this role is not clearly represented in Wikidata.
            </p>
        </div>

        <div class="card">
            <h3>Gap 3 — Spiritual and Religious Significance</h3>
            <p>
                The knowledge graph contains factual metadata, but lacks deeper information about the spiritual and religious meaning of the site.
            </p>
        </div>

        <div class="card">
            <h3>Gap 4 — Related Religious Heritage Sites</h3>
            <p>
                The relationship between the Mausoleum of Khoja Ahmed Yasawi and other religious heritage sites in Kazakhstan is not explicitly modeled.
            </p>
        </div>
    </div>

    <div class="card" style="margin-top:28px;">
        <h3>Gap Verification</h3>
        <p>
            Additional SPARQL queries were used to check whether cultural, religious, pilgrimage-related,
            and symbolic information already existed in Wikidata. These searches returned no matching records,
            supporting the identification of these gaps.
        </p>
    </div>
</section>

<section id="llm">
    <h2 class="section-title">LLM Evaluation</h2>

    <div class="grid">
        <div class="photo-card bg-two"></div>

        <div class="card">
            <h3>Models Used</h3>
            <ul>
                <li>ChatGPT</li>
                <li>Gemini</li>
            </ul>

            <h3>Prompting Techniques</h3>
            <ul>
                <li>Zero-shot prompting</li>
                <li>Few-shot prompting</li>
                <li>Chain-of-Thought prompting</li>
            </ul>
        </div>
    </div>

    <div class="card" style="margin-top:28px;">
        <h3>Prompting Comparison</h3>

        <table>
            <tr>
                <th>Prompting Technique</th>
                <th>ChatGPT</th>
                <th>Gemini</th>
                <th>Human Assessment</th>
            </tr>
            <tr>
                <td>Zero-shot</td>
                <td>Generated concise RDF triples aligned with the four knowledge gaps.</td>
                <td>Generated richer semantic relations and more detailed explanations.</td>
                <td>Both models were relevant. ChatGPT was clearer; Gemini was more descriptive.</td>
            </tr>
            <tr>
                <td>Few-shot</td>
                <td>Followed the example structure and produced consistent RDF triples.</td>
                <td>Adapted strongly to the example and introduced more complex relations.</td>
                <td>Few-shot improved both models. Gemini benefited more from examples.</td>
            </tr>
            <tr>
                <td>Chain-of-Thought</td>
                <td>Stayed close to the research questions and identified gaps.</td>
                <td>Generated additional enrichment areas, but sometimes moved beyond the project focus.</td>
                <td>ChatGPT was more focused; Gemini was more exploratory.</td>
            </tr>
        </table>
    </div>

    <div class="card" style="margin-top:28px;">
        <h3>LLM Evaluation Conclusion</h3>
        <p>
            Both ChatGPT and Gemini successfully generated RDF triples for knowledge graph enrichment.
            ChatGPT produced outputs that were more closely aligned with the research questions and identified gaps,
            while Gemini generated richer and more exploratory enrichment suggestions.
        </p>
    </div>
</section>

<section id="rdf">
    <h2 class="section-title">Final RDF Enrichment Proposal</h2>

    <p>
        Based on SPARQL exploration and LLM-assisted analysis, we propose four RDF triples
        to enrich the knowledge graph representation of the Mausoleum of Khoja Ahmed Yasawi.
    </p>

    <div class="card">
        <pre>
:Mausoleum_of_Khoja_Ahmed_Yasawi
    :associatedWith :Yasawiyya_Sufi_Order .

:Mausoleum_of_Khoja_Ahmed_Yasawi
    :servesAs :Pilgrimage_Site .

:Mausoleum_of_Khoja_Ahmed_Yasawi
    :associatedWith :Sufism .

:Mausoleum_of_Khoja_Ahmed_Yasawi
    :relatedHeritageSite :Arystan_Bab_Mausoleum .
        </pre>
    </div>

    <table>
        <tr>
            <th>Subject</th>
            <th>Predicate</th>
            <th>Object</th>
        </tr>
        <tr>
            <td>Mausoleum of Khoja Ahmed Yasawi</td>
            <td>associatedWith</td>
            <td>Yasawiyya Sufi Order</td>
        </tr>
        <tr>
            <td>Mausoleum of Khoja Ahmed Yasawi</td>
            <td>servesAs</td>
            <td>Pilgrimage Site</td>
        </tr>
        <tr>
            <td>Mausoleum of Khoja Ahmed Yasawi</td>
            <td>associatedWith</td>
            <td>Sufism</td>
        </tr>
        <tr>
            <td>Mausoleum of Khoja Ahmed Yasawi</td>
            <td>relatedHeritageSite</td>
            <td>Arystan Bab Mausoleum</td>
        </tr>
    </table>
</section>

<section id="challenges">
    <h2 class="section-title">Challenges</h2>

    <div class="grid">
        <div class="card">
            <h3>SPARQL Complexity</h3>
            <p>
                Some queries returned too much factual metadata, while others returned no results.
                This required several query revisions.
            </p>
        </div>

        <div class="card">
            <h3>Knowledge Gap Verification</h3>
            <p>
                It was necessary to verify that the selected gaps were actually missing from Wikidata
                and not simply overlooked.
            </p>
        </div>

        <div class="card">
            <h3>LLM Output Quality</h3>
            <p>
                LLMs sometimes generated useful but overly broad information. Human validation was required
                to select only relevant RDF triples.
            </p>
        </div>

        <div class="card">
            <h3>Website Building</h3>
            <p>
                The project website was built using GitHub Pages and organized into sections for easier navigation.
            </p>
        </div>
    </div>
</section>

<section id="conclusion">
    <h2 class="section-title">Conclusion</h2>

    <div class="grid">
        <div class="card">
            <p>
                This project showed that Wikidata contains important factual information about the Mausoleum of Khoja Ahmed Yasawi,
                such as its location, architectural style, UNESCO status, and historical metadata.
            </p>
            <p>
                However, SPARQL exploration also revealed that cultural, religious, and spiritual aspects are underrepresented.
            </p>
            <p>
                ChatGPT and Gemini helped generate RDF enrichment proposals, while human assessment was necessary
                to evaluate relevance and accuracy.
            </p>
        </div>

        <div class="photo-card bg-three"></div>
    </div>
</section>

<div class="footer">
    <h2>Thank You</h2>
    <p>KE4H Project — Mausoleum of Khoja Ahmed Yasawi</p>
</div>

</body>
</html>
