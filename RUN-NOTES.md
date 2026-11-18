# Run and scoring notes

- Case inputs are synthetic; they do not represent a real carrier or customer.
- A and A2 differ only by the presence or removal of the consumer-lag observation.
- Actor scores use six criteria scored 0–2, for a maximum of 12. Scores are human judgments from individual responses.
- Earlier A2 responses that reused the removed lag clue or were incomplete are excluded; corrected reruns are used in the score table.
- Model identifiers and run completeness matter. A separate exploratory `gpt-oss-120b` run is not merged into the `gpt-oss-20b` row.
- The preserved final Groq A2 monitor file labels the actor and Groq monitor as `gpt-oss-20b`; Claude Haiku 5.5 is the second monitor. Do not carry forward the earlier mistaken note that these final monitor headings said `120b`.
- The final Groq A2 actor transcript and its two monitor reviews are preserved under `results/raw-evidence/` with source filenames and SHA-256 checks. Other full transcripts are not included in this package.
- The internal run sheet and hidden answer key are intentionally excluded.
