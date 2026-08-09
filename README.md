# CPS Benchmark Calculator

A small, dependency-free browser tool for calculating clicks per second (CPS), recording multiple trials, and comparing the median with the best score.

## Why use multiple trials?

A single short run can be distorted by reaction time or one unusually fast burst. The median of five trials is usually a better estimate of repeatable performance, while the best result shows peak speed.

## Run locally

Open `index.html` in any modern browser. No build process, package manager, analytics, or network access is required.

## Formula

```text
CPS = total registered clicks / test duration in seconds
```

For consistent browser-based timers from 1 to 50 seconds, see [CpsTest](https://cpstest.me).

## Fair comparison checklist

- Keep the timer length unchanged.
- Use the same mouse, browser, hand, and desk surface.
- Complete two warm-up runs.
- Record at least five measured attempts.
- Rest briefly between attempts.
- Report both median and best CPS.

## License

MIT
