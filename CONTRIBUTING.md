# Team workflow

1. Create an issue with a type, a priority and an iteration.
2. Create a branch from `main`, for example `feature/12-product-list` or `fix/20-stock-total`.
3. Open a pull request linked to the issue.
4. The other team member reviews it before it is merged.

Do not push features directly to `main`.

## Board

Columns: Pending, In progress, In review, Done. Each person has at most two tasks in progress.

## Definition of done

- Reviewed by the other team member
- Automated tests pass
- Acceptance criteria are met
- Documentation is up to date

## Security

Never commit passwords, tokens, `.env` files, certificates, signing keys or real customer and shop data.
