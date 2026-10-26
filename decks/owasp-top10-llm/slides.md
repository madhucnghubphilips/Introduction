---
marp: true
theme: default
paginate: true
html: true
size: 16:9
---

<!-- The OWASP Top 10 for LLM Applications (2025) training was designed and developed by CN Madhu (madhu.cn@philips.com). This program combines industry-relevant content and practical labs to showcase real-world AI security risks, vulnerabilities, and defense strategies in healthcare environments. -->

<style>
section {
  background: #ffffff;
  color: #111827;
  font-family: "Aptos", "Segoe UI", Arial, sans-serif;
  letter-spacing: 0;
}

h1, h2, h3 {
  color: #111827;
  letter-spacing: 0;
}

h1 {
  font-size: 2.4rem;
}

h2 {
  font-size: 1.8rem;
}

p, li, td, th {
  font-size: 1.02rem;
}

strong {
  color: #0f4c81;
}

code, pre {
  background: #f8fafc;
  border: 1px solid #d0d7de;
  border-radius: 6px;
  color: #111827;
}

pre {
  line-height: 1.22;
  padding: 0.55rem 0.7rem;
}

table {
  width: 100%;
  border-collapse: collapse;
}

td, th {
  border: 1px solid rgba(148, 163, 184, 0.28);
  padding: 0.45rem 0.6rem;
}

section.lead {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

section.lead h1 {
  font-size: 3.2rem;
  margin-bottom: 0.4rem;
}

section.lead p {
  color: #374151;
  font-size: 1.35rem;
}

section.image h2 {
  background: rgba(255, 255, 255, 0.9);
  border-radius: 6px;
  display: inline-block;
  font-size: 1rem;
  left: 1rem;
  padding: 0.35rem 0.75rem;
  position: absolute;
  top: 1rem;
}

.cols {
  align-items: stretch;
  display: grid;
  gap: 1rem;
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.panel {
  background: #f8fafc;
  border: 1px solid #d0d7de;
  border-radius: 8px;
  min-width: 0;
  padding: 0.75rem;
}

.panel h3 {
  margin-top: 0;
}

.panel p {
  font-size: 0.92rem;
}

.panel pre {
  font-size: 0.82rem;
}
</style>

<!-- _class: lead -->


<!-- _class: image -->

![bg contain](../../Resources/Introduction-1.png) 

---

<!-- _class: lead -->


---

