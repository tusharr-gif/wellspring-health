<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Keep the wellbeing experience as a client-side interactive page with shared design-system controls; guidance and check-ins do not require accounts or persist sensitive health data.
- Define the visual theme in src/styles.css using semantic tokens so all experiences share consistent accessible styling.
- Pre-optimize directly used UI dependencies alongside the template's React dependencies in Vite; this prevents late dependency discovery from mixing React module versions in an already-open preview.
