<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Coverage](./puppeteer.coverage.md) &gt; [stopJSCoverage](./puppeteer.coverage.stopjscoverage.md)

## Coverage.stopJSCoverage() method

<b>Signature:</b>

```typescript
stopJSCoverage(): Promise<CoverageEntry[]>;
```
<b>Returns:</b>

Promise&lt;[CoverageEntry](./puppeteer.coverageentry.md)<!-- -->\[\]&gt;

Promise that resolves to the array of coverage reports for all scripts.

## Remarks

JavaScript Coverage doesn't include anonymous scripts by default. However, scripts with sourceURLs are reported.
