# Audio Asset Policy

## Built-in product cues
The built-in activity-start and transition cues are generated procedurally in the browser with the Web Audio API. No third-party music, recordings, samples, or sound-effect files are bundled with the product.

## Commercial releases
Before release, maintain an audio manifest recording the source, creator, license, acquisition date, and required attribution for every bundled audio asset. Acceptable sources are:

- Original audio commissioned under a written work-for-hire or copyright-assignment agreement.
- Audio created internally and documented as company-owned.
- CC0/public-domain audio with a saved copy of the license and source page.
- Commercially licensed audio whose license explicitly permits embedding, redistribution, modification, and use in a paid software product.

Do not bundle assets marked NonCommercial, assets copied from streaming services, or assets whose license cannot be verified. CC BY assets require attribution; CC BY-SA may impose share-alike obligations and should receive legal review before bundling.

## Teacher-provided audio
Teacher uploads and direct links are user-provided content. Production terms should require users to have permission to use that content and should provide removal/reporting procedures. The product should not ship teacher-uploaded content to other customers.

## Release checklist
1. Preserve source files and license evidence.
2. Record SHA-256 hashes and filenames in the release manifest.
3. Verify attribution text where required.
4. Confirm the license covers commercial software distribution.
5. Obtain counsel review before adding third-party music or recordings to the default library.

## Built-in one-minute activity tune

The default one-minute activity tune is generated at runtime from original note and timing instructions written for this application. It contains no copied recording, sample, or third-party audio file. Keep the source code and dated development records with the product's intellectual-property files. This is a product-development safeguard, not a legal opinion; obtain counsel review before a commercial release.
