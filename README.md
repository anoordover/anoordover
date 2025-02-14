## Hi there 👋

I work for Het CAK in the Netherlands and develop backend functionality in .Net.

Currently we are implementing an exchange with member states using EESSI for "Actual cost claims" (S_BUC_19, AW_BUC_05) and "Fixed amounts" (S_BUC_21).
The technologies we use are:
- EF Core
- Oracle DB
- ActiveMq classic
- MassTransit (@phatboyg)

## Aspire CommunityToolkit

### ActiveMQ

Our usage of ActiveMq was my drive to implement an [ActiMq Classic](https://activemq.apache.org/components/classic/) host component for the Aspire CommunityToolkit that could be used by ActiveMq.
I did this because MassTransit expects a scheme "activemq" in the connectionstring.
[ActiveMq Artemis](https://activemq.apache.org/components/artemis/) is now also available.

### Papercut SMTP

I also implemented a hosting component for testing integrations with SMTP using [Papercut SMTP](https://github.com/ChangemakerStudios/Papercut-SMTP).

<!--
**anoordover/anoordover** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
