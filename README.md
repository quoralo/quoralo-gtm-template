# Quoralo AI Chat Agent — Google Tag Manager template

Adds the [Quoralo](https://www.quoralo.com) AI chat agent to any website that uses Google Tag Manager: a chat button that answers your visitors 24/7 from the information you give it.

**Requires a Quoralo account.** A free plan is available, with no card required.

## Setup

1. In Google Tag Manager, open **Templates → Search Gallery**, find **Quoralo AI Chat Agent** and add it to your workspace.
2. Create a new tag with this template.
3. In **Agent identifier**, paste the identifier of your agent (for example `my-agent`) or its chat link (`https://www.quoralo.com/c/my-agent`). You find it in your Quoralo dashboard: open your agent, then click **Share**.
4. Add the trigger **All Pages**, save, then publish your container.

Colour, position and welcome bubble are set in your Quoralo dashboard.

## What the template does

It loads one script, `https://www.quoralo.com/api/widget/<your-agent>`, once per page (permission: *Injects scripts*, limited to that address). The chat opens in an iframe served by quoralo.com and does not change your site's styles. The template itself stores and sends no data. Conversations are handled by Quoralo: https://www.quoralo.com/privacy

## Support

https://www.quoralo.com/contact

---

### En français

Ce modèle ajoute l'agent IA Quoralo sur tout site qui utilise Google Tag Manager. Dans le tag, collez l'identifiant de votre agent (ou son lien de chat), ajoutez le déclencheur « All Pages » et publiez le conteneur. Un compte Quoralo est nécessaire (formule gratuite disponible).

## License

Apache License 2.0 — see [LICENSE](LICENSE).
