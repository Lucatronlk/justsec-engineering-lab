<p align="center"><img src="assets/justsec/justsec-engineering-lab-wordmark-readme.png" alt="justsec-engineering-lab" width="100%"></p>

<p align="center"><strong>No shortcuts — Just security.</strong></p>

<p align="center"><img src="assets/brand/lab-tagline.svg" alt="// Always learning. Always building. Always breaking. Always securing. Always improving." width="100%"></p>

## <img src="assets/icons/compass.svg" width="22" height="22" alt=""> Goal

This repo is a place to build, break, solve, explore and stay curious. It’s where “What does this button do?” turns into learning by doing.

The lab aims to spin up disposable environments with intentionally vulnerable targets. We can run authorized pentests, test detections and see how hardening changes affect the results.

To push the scanners to their limits, the lab will call the reusable workflows from:

<p align="center"><a href="https://github.com/Lucatronlk/justsec-cicd-blueprints"><img src="assets/justsec/JustSec%20CI_CD%20blueprints%20gradient%20wordmark.png" alt="JustSec CI/CD Blueprints — open repository" width="420"></a></p>

Scanner implementations stay in that repository; the lab will only add callers when needed.

Environments are planned to be provisioned with IaC, making experiments repeatable and results comparable. They’ll be torn down between runs, and anything left running won’t hold state we need to keep.

<p align="center"><img src="assets/icons/shield.svg" width="22" height="22" alt=""> Security engineering · <img src="assets/icons/flask.svg" width="22" height="22" alt=""> Pentest · <img src="assets/icons/radar.svg" width="22" height="22" alt=""> Attack simulation · <img src="assets/icons/build-code.svg" width="22" height="22" alt=""> DevSecOps · <img src="assets/icons/terminal.svg" width="22" height="22" alt=""> Lab · <img src="assets/icons/blocks.svg" width="22" height="22" alt=""> Infrastructure as code</p>

<p align="center"><img src="assets/brand/section-divider.svg" width="100%" height="6" alt=""></p>

## <img src="assets/icons/star.svg" width="22" height="22" alt=""> What you get


<table>
  <tr>
    <td align="center" valign="top" width="33%"><img src="assets/icons/shield.svg" width="28" height="28" alt=""><br><strong>Security engineering</strong><br><sub>Compare findings and controls across repeatable runs; record what a hardening change actually improves.</sub></td>
    <td align="center" valign="top" width="33%"><img src="assets/icons/flask.svg" width="28" height="28" alt=""><br><strong>Pentest</strong><br><sub>Use intentionally weak, isolated targets to practise authorized testing without treating a live system as a lab.</sub></td>
    <td align="center" valign="top" width="33%"><img src="assets/icons/radar.svg" width="28" height="28" alt=""><br><strong>Attack simulation</strong><br><sub>Repeat bounded scenarios, capture observations and compare detection before and after changes.</sub></td>
  </tr>
  <tr>
    <td align="center" valign="top"><img src="assets/icons/build-code.svg" width="28" height="28" alt=""><br><strong>DevSecOps</strong><br><sub>Plan thin, SHA-pinned callers of CI/CD Blueprints reusable scans and severity gate; keep scanner implementations upstream.</sub></td>
    <td align="center" valign="top"><img src="assets/icons/terminal.svg" width="28" height="28" alt=""><br><strong>Lab</strong><br><sub>Design disposable environments with clear boundaries, teardown and no persistent state worth keeping.</sub></td>
    <td align="center" valign="top"><img src="assets/icons/blocks.svg" width="28" height="28" alt=""><br><strong>Infrastructure as code</strong><br><sub>Define environments declaratively so the same setup and teardown can be reviewed and repeated.</sub></td>
  </tr>
</table>

<p align="center"><img src="assets/brand/section-divider.svg" width="100%" height="6" alt=""></p>

## <img src="assets/icons/doc.svg" width="22" height="22" alt=""> License

The repository's software is licensed under the [MIT License](LICENSE). Artwork in `assets/`, including wordmarks and icons, is **not covered by the MIT license**; see the [brand artwork notice](assets/NOTICE.md) for reuse restrictions and publication caveats.