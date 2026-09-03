---
venue: "Division of Psychiatry, University College London"
address: "online"
country: "gb"
language: "en"
latitude: "51.5246"
longitude: "-0.1340"
humandate: "14, 21, and 28 October, and 4 November 2026"
humantime: "09:30–13:00 (Europe/London)"
startdate: 2026-10-14
enddate: 2026-11-04
instructor: ["Justin C Yang", "Naomi Launders"]
helper: ["Stephanie Wu"]
email: ["justin.yang@ucl.ac.uk"]
collaborative_notes:
eventbrite:
what3words:
layout: workshop
---

<div class="card mb-3">
  <div class="card-body">
    <p>
      <strong>Reproducible Data Analysis for Mental Health Research</strong> is a four-session online workshop series for PhD students, postdoctoral researchers, and other research staff in the UCL Division of Psychiatry.
    </p>
    <p>
      The workshop is being run as a self-organised Carpentries <em>Mix &amp; Match</em> workshop. It uses selected episodes from the Software Carpentry <a href="https://swcarpentry.github.io/r-novice-gapminder/">R for Reproducible Scientific Analysis</a> and <a href="https://swcarpentry.github.io/python-novice-gapminder/">Plotting and Programming in Python</a> lessons, with live coding and practical exercises based on the Gapminder data.
    </p>
    <p class="mb-0">
      The R and Python strands each begin at introductory level. Learners are strongly encouraged to attend all four sessions for maximum benefit, as concepts and good practices introduced earlier in the series are reinforced throughout. If this is not possible, learners may attend either the R or Python strand; the second session in each strand builds on the first, so learners joining only Part 2 should already have equivalent foundational experience.
    </p>
  </div>
</div>

<div class="row g-3 pb-3">
  <div class="col-md-6">
    <div class="card h-100">
      <h5 class="card-header">The Carpentries</h5>
      <div class="card-body">
        <p>
          <strong><a href="https://carpentries.org">The Carpentries</a></strong> teaches foundational coding and data science skills to researchers through participatory, hands-on workshops.
        </p>
        <p class="mb-0">
          This workshop follows Carpentries teaching practices and uses established Software Carpentry lesson materials, while selecting the episodes most relevant to our audience and available teaching time.
        </p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100">
      <h5 class="card-header">Code of Conduct</h5>
      <div class="card-body">
        <p>
          Everyone participating in Carpentries activities is required to follow the <a href="https://docs.carpentries.org/policies/coc/">Carpentries Code of Conduct</a>.
        </p>
        <p class="mb-0">
          The workshop is intended to provide a supportive environment in which learners can ask questions, make mistakes, and work through exercises together.
        </p>
      </div>
    </div>
  </div>
</div>

<div class="card mb-3">
  <h5 class="card-header">Workshop Logistics</h5>
  <div class="card-body">
    <dl class="mb-0">
      <div class="row">
        <dt class="col-sm-2 py-2 px-3 bg-body-light text-body-secondary fw-bold">Who</dt>
        <dd class="col py-2 px-3 mx-0 mb-0">
          PhD students, postdoctoral researchers, and other research staff in the UCL Division of Psychiatry. No previous programming experience is required for the introductory R or Python sessions.
        </dd>
      </div>
      <div class="row">
        <dt class="col-sm-2 py-2 px-3 bg-body-light text-body-secondary fw-bold">Where</dt>
        <dd class="col py-2 px-3 mx-0 mb-0">
          Online. Joining instructions will be sent to registered participants before the workshop.
        </dd>
      </div>
      <div class="row">
        <dt class="col-sm-2 py-2 px-3 bg-body-light text-body-secondary fw-bold">When</dt>
        <dd class="col py-2 px-3 mx-0 mb-0">
          14, 21, and 28 October, and 4 November 2026, 09:30–13:00 (Europe/London).
        </dd>
      </div>
      <div class="row">
        <dt class="col-sm-2 py-2 px-3 bg-body-light text-body-secondary fw-bold">Format</dt>
        <dd class="col py-2 px-3 mx-0 mb-0">
          Four online half-day sessions with live coding, exercises, two short breaks each morning, and regular opportunities for questions. The sessions are designed for active participation rather than passive viewing.
        </dd>
      </div>
      <div class="row">
        <dt class="col-sm-2 py-2 px-3 bg-body-light text-body-secondary fw-bold">Contact</dt>
        <dd class="col py-2 px-3 mx-0 mb-0">
          Please email <a href="mailto:justin.yang@ucl.ac.uk">justin.yang@ucl.ac.uk</a> with questions about the workshop.
        </dd>
      </div>
    </dl>
  </div>
</div>

<div class="card mb-3">
  <h5 class="card-header">Surveys</h5>
  <div class="card-body">
    <div class="row g-3">
      <div class="col-sm-6">
        <div class="card text-center h-100">
          <div class="card-body">
            <h5 class="card-title">Pre-Workshop Survey</h5>
            <p class="card-text">Please complete the Carpentries pre-workshop survey before your first session.</p>
            <a href="{{ site.pre_survey }}{{ site.github.project_title }}" class="btn btn-primary">Pre-Workshop Survey</a>
          </div>
        </div>
      </div>
      <div class="col-sm-6">
        <div class="card text-center h-100">
          <div class="card-body">
            <h5 class="card-title">Post-Workshop Survey</h5>
            <p class="card-text">Please complete the Carpentries post-workshop survey after your final session.</p>
            <a href="{{ site.post_survey }}{{ site.github.project_title }}" class="btn btn-primary">Post-Workshop Survey</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="card mb-3">
  <h5 class="card-header">Schedule</h5>
  <div class="card-body">
    {% include custom-schedule.html %}
  </div>
</div>

<hr/>

<h2 id="setup">Setup</h2>

<p>
  Please complete the relevant setup before the first session you plan to attend. You will need a computer on which you can install and run the required software, together with an up-to-date web browser. If possible, test that the software opens successfully before the workshop.
</p>

<div class="row g-3">
  <div class="col-md-6">
    <div class="card h-100">
      <h5 class="card-header">R sessions</h5>
      <div class="card-body">
        <p>
          Install the latest versions of <a href="https://cran.r-project.org/">R</a> and <a href="https://posit.co/download/rstudio-desktop/">RStudio Desktop</a> before 14 October.
        </p>
        <p>
          The R lesson uses several packages during the workshop, including <code>gapminder</code>, <code>ggplot2</code>, <code>dplyr</code>, <code>tidyr</code>, and <code>knitr</code>. We will provide final package-installation instructions to registered learners before the workshop.
        </p>
        <p class="mb-0">
          See the <a href="https://swcarpentry.github.io/r-novice-gapminder/">R lesson setup and materials</a> for further details.
        </p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100">
      <h5 class="card-header">Python sessions</h5>
      <div class="card-body">
        <p>
          Install Python 3 and JupyterLab before 28 October. The Software Carpentry lesson recommends installing Python through <a href="https://www.anaconda.com/download">Anaconda</a>.
        </p>
        <p>
          You will also need the Gapminder data used in the lesson. Download and unzip the <a href="https://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip">Python Gapminder data</a> before the first Python session.
        </p>
        <p class="mb-0">
          See the <a href="https://swcarpentry.github.io/python-novice-gapminder/">Python lesson setup and materials</a> for further details.
        </p>
      </div>
    </div>
  </div>
</div>

<h2 id="accessibility">Accessibility</h2>
<p>
  We want the workshop to be accessible and inclusive. If there is anything we can reasonably do to support your participation, please contact <a href="mailto:justin.yang@ucl.ac.uk">justin.yang@ucl.ac.uk</a> before the workshop.
</p>

<h2 id="recordings">Recordings</h2>
<p>
  Carpentries workshops are designed around live participation, coding, and exercises. Participants should therefore plan to attend in real time. Recordings are not currently planned.
</p>
