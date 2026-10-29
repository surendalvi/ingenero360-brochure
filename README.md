# Ingenero website

Production: https://suite.ingenero360.ai/

The static website is served from the repository root by GitHub Pages. Preserve `CNAME` and `.nojekyll`. Upload all referenced assets and retain directory capitalization. No Node build or server application is required.

The home video, fonts, icons, brochures, whitepapers, agent illustrations, dashboard screenshots and demo videos are included in this repository. Email actions open an Outlook Web draft addressed to solutions@ingenero.ai; visitors review and send it themselves.

## Editing and deployment

The canonical editable source is the Marketing Brochure folder on the owner's computer. Copy the verified deployment files into this repository, commit, and push to main. Keep the existing GitHub Pages domain settings. See DEPLOYMENT.md for hosting details.

## Rollback

The previous production commit is `0e399eae5124ffc1f7febe5add3c9a7d60453bf5`. A backup branch is retained before deployment. To roll back a published update, revert its deployment commit and push the revert to main.
