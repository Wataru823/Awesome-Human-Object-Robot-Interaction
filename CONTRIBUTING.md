# Contributing

Thanks for helping. This list is read by people who may not speak English as a first language, so **clear writing matters as much as the papers**.

## What fits

- Papers about a human and a robot using the **same object**: hand-object perception, affordance, imitation from human video, grasping, handover, evaluation with people.
- Datasets, benchmarks, and open-source tools that make that work possible.
- Published or arXiv papers only. For blog posts, only if they contain an experiment someone else can reproduce.

If a paper is only loosely related (for example, general robot navigation), it probably belongs in another list.

## Add one entry

1. Fork the repository and create a branch.
2. Add one bullet at the end of the right section, in this format:

   ```
   - **[Paper title](https://link)** - *Venue Year* - one line on why it matters.
   ```

3. Open the link yourself and check that the title matches the page.
4. Open a pull request. **One paper per pull request** is fine and gets reviewed faster.

## Writing rules

| Rule | Why |
| :--- | :--- |
| 20 words or fewer for the "why" line | Long lines are not read |
| No marketing words ("groundbreaking", "state of the art") | Readers want facts |
| Say what the paper *does*, not what it promises | Promises age badly |
| Avoid idioms and slang | Many readers are not native English speakers |
| Use the title as published | Readers must be able to find the paper |

Good: `Learns where to push or pull on a 3D object, then acts there.`

Bad: `A revolutionary breakthrough that finally solves robotic manipulation!`

## What we check before merging

- The link opens and shows the cited paper.
- The paper exists on arXiv or in a venue.
- The section fits.
- The line is plain English and factual.
- No duplicate entry.

## Fixing a broken link

Small fix, still a pull request. Please change only the URL.

## Labels

- `good first issue` - add one paper or fix one link.
- `needs-verification` - the paper or the claim needs a second check.

## Code of conduct

Be kind. Disagree with the claim, not the person. Reports go to the maintainer.
