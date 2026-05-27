<div align="center">
<h2 align="center">
  <img src="assets/logo-1779724213346.svg" alt="Solarch Logo" width="60" align="center" /> 
  &nbsp;&nbsp;Solarch&nbsp;&nbsp;
</h2>
  <p>AI-Powered Architectural Pipeline & Agentic DevTool</p>
<br/>

*Your entire workspace, on one canvas. | AI that ships. No more hallucinations.*

<br />

[![License](https://img.shields.io/badge/License-PolyForm%20NC%201.0-orange.svg)](./LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/fatalerrorist/Solarch?style=flat-square)](https://github.com/fatalerrorist/Solarch/stargazers)
[![Contributors](https://img.shields.io/github/contributors/fatalerrorist/Solarch?style=flat-square)](https://github.com/fatalerrorist/Solarch/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/fatalerrorist/Solarch?style=flat-square)](https://github.com/fatalerrorist/Solarch/commits/main)

<br />

<img src="./assets/AICanvasBuilding.gif" width="100%" alt="Solarch — AI builds architecture from a single prompt" />

<br />

[**Why Solarch?**](#-why-solarch) &nbsp; • &nbsp; [**Gallery**](#-gallery) &nbsp; • &nbsp; [**Features**](#-features) &nbsp; • &nbsp; [**Philosophy**](#-the-philosophy) &nbsp; • &nbsp; [**Get Involved**](#-get-involved)

</div>

<br />

---

## ✦ Why Solarch?

Most AI tools hallucinate code and hope the architecture catches up. **Solarch flips that.**

It writes **architecture** first — a structured, navigable, editable graph of your system — and only invokes AI where AI actually adds value: the algorithm, not the API surface.

*   **One canvas for the whole system:** Controllers, services, repositories, tables, DTOs, and the semantic edges between them.
*   **Sketch-to-Architecture Pipeline:** Draw freehand, hit Refine, get a structured graph.
*   **Constructors:** Opinionated, pre-wired patterns (auth, CRUD, event pipelines) that ship 80% of your structure on click.
*   **Surgical AI:** Algorithm-only completion in the remaining 20%; no hallucinated APIs, no fabricated endpoints.
*   **First-Class Semantic Edges:** *Calls*, *queries*, *publishes*, *subscribes*, *throws* — visualized natively, not as generic arrows.
*   **Per-Type Editors:** Tables get column grids, services get method tables, controllers get endpoint rows.
*   **Live Instruct Mode:** Chat with your architecture; every answer cites the exact nodes it references and focuses the canvas.

---

## ✦ Gallery

Solarch meets you where you are. See how ideas transform into structured, provable architecture in seconds.

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <b>1. Start with a prompt</b><br/>
      A prompt. A scribble. A half-formed idea. Type what you want to build — the architecture forms in front of you.<br/><br/>
      <img src="./assets/AIInputTyping.gif" width="100%" alt="AI input typing" />
    </td>
    <td width="50%" valign="top">
      <b>2. Or draw a sketch</b><br/>
      Draw it on a napkin instead. Hit <b>Refine</b>. Your sketch becomes a structured architecture in seconds.<br/><br/>
      <img src="./assets/SketchToArchitecture.gif" width="100%" alt="Sketch to architecture" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>3. Watch it build itself</b><br/>
      Nodes appear with zen pop animations, edges flow with the right semantics. The whole shape, in one shot.<br/><br/>
      <img src="./assets/AICanvasBuilding.gif" width="100%" alt="AI canvas building" />
    </td>
    <td width="50%" valign="top">
      <b>4. A library of constructors</b><br/>
      One click expands an entire pattern: nodes, edges, methods, types. Templates that ship, not stubs.<br/><br/>
      <img src="./assets/TemplateLibrary.gif" width="100%" alt="Template library" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>5. Connect anything to anything</b><br/>
      Hover a port, drag, snap. Semantic relationships are first-class citizens carrying meaning.<br/><br/>
      <img src="./assets/EdgeConnecting.gif" width="100%" alt="Edge connecting" />
    </td>
    <td width="50%" valign="top">
      <b>6. Every node, fully editable</b><br/>
      Double-click any node. Methods, fields, validation rules — edit inline with a contextual inspector.<br/><br/>
      <img src="./assets/InspectorReveal.gif" width="100%" alt="Inspector reveal" />
    </td>
  </tr>
</table>

<div align="center">
  <b>Ask your architecture anything</b><br/>
  Switch to Instruct mode and chat with your design. Every citation is a live chip that focuses the canvas.<br/><br/>
  <img src="./assets/InstructQuestion.gif" width="80%" alt="Instruct mode" />
</div>

---

## ✦ Features

<table>
  <tr>
    <td width="50%" valign="top">
      <ul>
        <li><b>Three-Mode Pipeline:</b> <code>Sketch</code> → <code>Refine</code> → <code>Generate</code></li>
        <li><b>Native SVG Sketch Surface:</b> Freehand, stencils, frames, multi-tab workspace</li>
        <li><b>AI-Driven Refine:</b> LangGraph + DeepSeek inference</li>
        <li><b>21 First-Class Node Families:</b> Table, DTO, Model, Service, Worker, Controller, APIGateway, Repository, and more.</li>
        <li><b>16 Semantic Edge Kinds:</b> <code>CALLS</code>, <code>QUERIES</code>, <code>WRITES</code>, <code>PUBLISHES</code>, <code>SUBSCRIBES</code>...</li>
        <li><b>Mermaid Export:</b> Every graph round-trips for external tooling.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <ul>
        <li><b>Constructor Library:</b> One-click expansion into fully-wired node groups.</li>
        <li><b>Purpose-Built Inspectors:</b> Column grids for tables, method tables for services.</li>
        <li><b>Instruct Mode:</b> Q&A with live node chips and per-turn context.</li>
        <li><b>Edge Bundling & Routing:</b> Obstacle-aware paths.</li>
        <li><b>Local-First Persistence:</b> Your project is the canonical model.</li>
        <li><b>Aydınlık Blueprint Design:</b> Paper zemin, semantic colors, hairline grid.</li>
      </ul>
    </td>
  </tr>
</table>

---

## ✦ The Philosophy

> **Solarch doesn't write code. It writes architecture.**
>
> The industry has spent two years trying to make LLMs write code. The result: confident hallucinations, ghost APIs, and codebases that compile but lie. The hallucination isn't a tuning problem — it's a category error.
> 
> Architecture is the level where structure is **provable**. A controller calls a service. A service queries a repository. A repository writes a table. These relationships are either present or not. They can't be hallucinated.

Solarch separates the two concerns:

1. **Constructors:** Deterministic, hand-authored, pre-wired patterns that ship the structural 80% of any backend. No AI, no risk. Just composition.
2. **Surgical AI:** Invoked only inside the algorithmic 20%. A specific business rule, the pricing curve, the retry policy. Where AI genuinely earns its keep.

**Predictable structure. Targeted intelligence. Zero hallucinated APIs.**

---

## ✦ Get Involved

We welcome feedback, discussions, and contributions. 

- 💬 [**GitHub Discussions**](https://github.com/fatalerrorist/Solarch/discussions) — Feature requests, design feedback, questions.
- 🐛 [**Issues**](https://github.com/fatalerrorist/Solarch/issues) — Bug reports, regressions.
- 🛠️ [**Contributing Guide**](./CONTRIBUTING.md) — Local setup, conventions, commit style.

<br/>

## ✦ License

[PolyForm Noncommercial License 1.0.0](./LICENSE) — © 2026 Ugur Akdogan.

**Free** for personal use, research, education, and non-profit organizations. Source is open: fork, learn, modify, share — go for it. <br/>
**Commercial use requires a separate license** — reach out at [info@solidea.tech](mailto:info@solidea.tech).

<br/>
<div align="center">
  <b>See. Understand. Plan.</b><br/>
  In one shot.<br/><br/>
  <img src="assets/logo-1779724213346.svg" width="30" style="opacity: 0.5;" /><br/>
  <b>Solarch.</b>
</div>
