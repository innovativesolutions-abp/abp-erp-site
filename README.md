# ABA ERP public presentation

Static presentation and privacy notice for ABA ERP / ABP ERP and ABP ERP Messaging.

## Boundaries

- Public content only. The application source, private records and credentials are not included.
- GitHub Pages hosts presentation pages, not the ERP application, authentication, payments or transactions.
- No runtime dependencies, JavaScript, analytics, cookies or external font requests.
- Relative links work both under the project Pages URL and the selected custom domain `abaapp.alphabyte.pro`.
- English platform presentation; privacy notice in English and Polish.

## Preview

Serve this directory with any static HTTP server. For example: `php -S 127.0.0.1:8772 -t .`.

## Publication

Publish `main`, root directory, using GitHub Pages. Verify public HTML and assets before configuring the custom domain. The custom domain must be bound to this repository before its DNS CNAME is added. DNS must point `abaapp.alphabyte.pro` to `innovativesolutions-abp.github.io`, without a repository path. Enable HTTPS enforcement after GitHub provisions the certificate. Do not change the ERP domain or its DNS.

The canonical privacy route is `/privacy.html`, with deletion instructions at `/privacy.html#deletion` and a WhatsApp section at `/privacy.html#whatsapp`. These pages do not install a provider subscription or make an unpublished Meta application live.

Update the policy before enabling materially new data processing. It describes declared operator practices and inspected application behavior; it is not legal certification.

## Rollback

Revert the relevant site commit to restore content. A custom-domain removal requires coordinated DNS cleanup to avoid a dangling CNAME. Do not delete the site while DNS still points to it.
