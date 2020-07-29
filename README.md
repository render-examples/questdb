# Deploy Shynet on Render

This repo can be used to deploy [Shynet] on Render.

- It uses the [official Shynet Docker image](https://hub.docker.com/r/milesmcc/shynet).
- [Render Databases](https://render.com/docs/databases) are used to spin up a fully managed PostgreSQL instance.

## Deployment

### One Click Deploy

Use the button below to deploy Shynet on Render.

[![Deploy to Render](http://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

After deployment, use Render **Shell** to set up your account with those 3 commands:

1. Set your email with `./manage.py registeradmin your-email@example.com`. You will be prompted with a temporary password. Save it.
2. Add your onrender.com domain with `./manage.py hostname your-shynet-domain.onrender.com`.
3. Set your whitelabel with `./manage.py whitelabel "Header for your Shynet site"`. It will be shown at the top of your Shynet site.

### Manual Deployment

See the guide at https://render.com/docs/deploy-shynet.

If you need help, chat with us at https://render.com/chat.

[shynet]: https://github.com/milesmcc/shynet
