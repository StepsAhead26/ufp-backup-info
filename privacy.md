# UFP Backup Privacy Policy

Last updated: 8 October 2026

## Operator and purpose

UFP Backup is operated by Steps Ahead Pvt Ltd for authorized administrators to maintain encrypted backups of its UFP damages-module database.

## Google Drive access

The tool uses Google OAuth authorization to upload encrypted backups to a designated private Google Drive folder and retrieve those files for integrity checks and recovery testing.

Depending on the permission granted, Google Drive access may extend beyond that folder. The configured folder is a storage destination, not a restriction on the authorization itself.

Google authorization credentials are stored as protected GitHub Actions secrets. They are not published on this website or in the public information repository.

## Backup information

Database backups may contain business records and personal information recorded in the UFP application. Backup contents are encrypted before upload. The private decryption key is kept separately from the automated backup workflow.

## Service providers and use

GitHub Actions processes the backup job, and Google Drive stores the encrypted backup files. Information is used for backup, integrity verification and recovery purposes—not advertising, sale or AI-model training.

## Retention and deletion

Authorized administrators manage backup retention and deletion. The initial workflow does not automatically delete older backups.

## Revoking access

The authorizing user can revoke access through their Google Account permissions. Revocation stops future authorized access but does not delete existing backup files. Administrators must delete those files separately.

## This website

This information-only website has no login, forms or added analytics. GitHub Pages may process technical request information under GitHub’s privacy policy.

## Contact

For questions or requests concerning backup information:

Tauqir.fazal@stepsahead.com.pk

[Return to UFP Backup](index.html)
