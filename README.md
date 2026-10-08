## Hi there 👋

I'm **Elnaz Alikarami** — I build systems that make scientific and clinical data
trustworthy.

I came to software from neuroscience. Human brain imaging taught me how research data
actually goes wrong: fragmented across incompatible systems, cleaned by hand, corrected
in ways nobody can reconstruct six months later. I now build the infrastructure that
stops that happening — with the domain knowledge to know which errors matter and which
are noise.

**Pronouns:** she/her

---

## 🔬 What I'm building

**[Clinical Data Fabric System](https://github.com/Elnazkarami/clinical-data-fabric-)** —
a clinical data platform: multi-source ingestion, CDISC-aligned standardisation,
validation, correction with full downstream propagation, and submission-ready
SDTM/ADaM export where every row traces back to what it was built from.

Built solo in Python. **Zero third-party runtime dependencies**, 677 tests at 92%
branch coverage, CI on 3.11–3.13. That repository is a public summary; the source is
available on request.

**[N-DOS](https://github.com/Elnazkarami/N-DOS)** — a system for recovering,
describing and querying animal neuroscience data that nobody organised. Point it at a
drive whose collector has graduated: it reads what is there without changing it,
reads inside the archives without extracting them, and rebuilds a usable layout —
subject, session, data type — from whatever structure already exists, labelling every
inference as an inference so you can correct it rather than trust it.

Then the parts that make it worth keeping. Full-text search across filenames, lab
notes, protocols and spreadsheets — including Word and Excel — where a hit in a
surgery log names the animals it mentions and points at their recording sessions.
Cohort queries that return three answers rather than two: matched, excluded, and
**cannot be ruled out**, because a session whose species nobody recorded is not a
session known not to be a mouse, and collapsing those two cases biases a cohort
quietly. Provenance from a figure back to the raw files behind it. Handoff to BIDS
and NWB. An optional local interface, for the people in a lab who do not work at a
command line.

Built solo in Python and released: `pip install ndos`. **Zero third-party runtime
dependencies** — it has to run on locked-down acquisition machines, and CI proves it by
running every module against a bare interpreter — with 444 tests on 3.9 and 3.13 across
Linux, macOS and Windows. Designed against real lab drives rather than synthetic
examples, which is where most of its design came from: the discovery that most of the
data on an inherited drive is sitting inside archives nothing had ever opened changed
the whole approach.

**Looking for labs to pilot it.** If you have a directory nobody fully understands any
more, that is exactly what it needs to meet — it takes about fifteen minutes and will
not move or change your data.
[Start here](https://github.com/Elnazkarami/N-DOS/discussions/21).

Alongside both: data harmonisation and reproducibility across multi-lab settings, and
research data management in neuroscience labs.

---

## 🛠 What I work with

**Engineering** — Python, SQL, REST API design, schema design, pytest, CI/CD, Git, Docker

**Data** — pandas, NumPy, data modelling, lineage and provenance, pipeline design

**Clinical & research standards** — CDISC (SDTM, ADaM), Define-XML, UCUM,
21 CFR Part 11, HIPAA/GDPR/PIPEDA handling of identifiers

**Research** — fMRI and neuroimaging analysis, experimental design, R, MATLAB

---

## 💬 Ask me about

- Designing data systems that survive an audit — lineage, provenance, and why
  "we fixed it in the spreadsheet" is a problem you find out about much later
- Running a research lab like a startup 🚀
- Brain imaging, cognitive neuroscience, and behavioural data
- Bridging the gap between the people who collect scientific data and the people who
  build systems for it

---

## 🤝 Let's connect

- 🌐 [elnazalikarami.com](https://www.elnazalikarami.com/)
- 💼 [LinkedIn](https://www.linkedin.com/in/elnaz-alikarami/)
- 🦋 [Bluesky](https://bsky.app/profile/elnaza.bsky.social)
- 📧 elnaz.karami@gmail.com

---

> Still mapping systems, just more than only neural ones. Same goal: make sense of the noise.
