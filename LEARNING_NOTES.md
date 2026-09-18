# Learning Notes

## AlphaSOC Analytics Engine

The lab introduced AlphaSOC Analytics Engine as the local analysis component and AlphaSOC Console as the interface used to manage credentials and review security-related telemetry.

## Network Flight Recorder

NFR was introduced as the network telemetry component. The installation process required downloading the appropriate Linux release, extracting it, locating the executable, and verifying it from the terminal.

## Troubleshooting observations

### File location matters

Running:

```bash
./nfr --help
```

from the wrong directory produced a file-not-found error. The command worked after navigating to the directory containing the NFR binary.

### GUI instructions can differ from the installed version

Some menu locations and file-manager options differed from the written lab instructions. I had to adapt rather than assume the interface would exactly match the lab handout.

### Integration is not the same as validation

Completing account registration and configuration does not prove that telemetry is flowing. The final validation step remained unclear, which is why the portfolio README explicitly documents it as unverified.

## Security hygiene

The original lab contained credential-generation steps. Any API keys, passwords, or account-specific information should never be committed to a public repository. This portfolio version intentionally excludes those screenshots and values.
