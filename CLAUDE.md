# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## The Lab GitHub Page

This is the GitHub Pages repository for the **ARIA AI Lab** (`aria-ai-lab.github.io`), an org Pages site served from `github.com/aria-ai-lab/aria-ai-lab.github.io`. The web site serves as the public interface of the lab I'm building at Peking University, as a new assistant professor starting his own lab.

The lab is called ARIR, short for Agency, Reasoning, Intelligence and Autonomy. The features the several directions we are working on. For agency, we mean agents that act autonomously with a specific value system to survive in the world. By Reasoning, we aim at models that can perform efficient reasoning tasks. By Intelligence, we build agents that perform super-human-level intelligence at specific tasks. And by Autonomy, we hatch robot systems that can integrate different directions of research we founded.

Your objective is to build the lab public facing interface using GitHub Page and Jekyll tool.

You should design it in a stylish but minimalist way, giving it a sense of technology but also warm and humane. I have provided a ```ARIA Logo.html``` for you to use where you find the ARIR logos in t3 part with favicon, horizontal lockup and primary logo. Design references the Brand system part below.

## Web Structure

Apart from the design, the web should include several sections. The home page, the people page, and the publication page.

### Home

The home page should first outline the objective of the lab (ARIR) with the general introduction, and elucidate the four elements in a dedicated section. The home page should also reserve a space for the latest lab news as a big running banner that shows pictures and the
corresponding short messages in a running manner. And finally, some latest news of the lab.

### People

The people page starts with the faculty, and then technical stuff, interns, and collaborators. For each part of the above part, each person should be allocated a round avatar, their affiliation, their role, and a final line of logos directing to their email, home page and github page (allow missing icons).

### Publication

The publication page lists chronologically all papers from the lab members. Each paper at least should have a title line, author line, a teaser, and a last line of icons that point to pdf, supplementary, poster, project page, dataset, github repo (some could be missing).

## Brand system (reuse these when building the site)

- **Palette:** Ink `#23201B` · Rust `#B4572F` · Clay `#D39A78` (dark-mode accent) · Paper `#F6F1E7`. Dark-mode surface `#1C1915`, dark paper/text `#F1EADB`.
- **Wordmark:** lowercase "aria", `Cormorant Garamond`, italic, weight 500 — ink on light, paper on dark. The staff/note motif is drawn in rust (light) or clay (dark).
- **Type:** headings/wordmark Cormorant Garamond; body/italic accents Newsreader; labels & mono in a system ui-monospace stack. Fonts are loaded from Google Fonts.
- **Nav / tagline:** "RESEARCH LAB", tagline "Agency · Reasoning · Intelligence · Autonomy", sample nav: Research · People · Publications · Join (Join in rust).
- **Min sizes:** wordmark 96px digital / 22mm print; favicon 16px.
