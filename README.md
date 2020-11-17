# Repro

1. Run `yarn install`
2. Run `yarn start`
3. Open `http://localhost:8080`
4. Increment the number in `src/bubble.tsx`
5. Observe the number increment in the browser
6. Increment the number in the comment in `src/guide.tsx`

Expected: No changes in the browser
Actual: The bubble number reverts to the previous number
