# V1 validation

October 15, 2026. Bounded presentation checks; no project pipelines or test suites rerun.

- Actual in-app browser viewport measurements: 320, 390, 768 and 1440 CSS pixels. Document width matched each viewport; all three project screenshots loaded. Initial Chrome viewport overrides did not apply to the intended tab and were excluded from these results.
- Desktop composition reviewed; native engineering-note disclosure controls opened via Enter (3/3), with visible keyboard focus. Navigation fragments resolve (0 missing targets).
- Four public demos returned HTTP 200: Inventory Intelligence (one earlier timeout, then successful), CounselReflect, FinRAG and Job Board Pipeline. Their application identities were checked in public pages/READMEs. No public demo writes, crawls or LLM requests were made.
- The owner selected a printable web résumé instead of publishing original PDFs. Current contact details use the explicit chat-supplied Gmail and phone; employment/education reflect the supplied current résumés.
- Public production deployed on Vercel Hobby from GitHub `main` at `b4a81a82e2ed882a295dc5c99128a3db2aec4d75`: https://portfolio-tan-eta-44.vercel.app/. Public page showed all five projects, all three loaded screenshots and no missing navigation fragments. GitHub profile README published at `8f0c6f84559103ed4fa63e7faeab64242ec0d6d3` and visibly links the portfolio and web résumé. Vercel import confirms instant branch previews; no throwaway PR was created.

This is a brief browser/link check, not a formal accessibility audit or a fresh validation of the project repositories' retained engineering results.

The generated Vercel domain is retained. No paid services, custom domain purchase or changes to project repositories / the existing GitHub Pages repository were made. Original résumé PDFs were not added to the published tree.
