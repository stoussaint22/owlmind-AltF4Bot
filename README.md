


<center>
<img src="docs/images/owlmind-banner.png">
<!--
<img src="docs/images/owlmind-banner.png" width="800">
-->

### [Get Started](#sample-section) | Underst | Extend | Contribute

</center>

# OwlMind 

OwlMind is a DIY Education Experimentation Platform being created by The Generative Intelligence Lab, at Florida Atlantic University. The focus is on education, helping students to get quick results whle implementing consumable GenAI-based Agentic System 

## Getting Started

1. Configure your Discord Bot 
2. Install OwlMind locally
3. Animate your Discord Bot with an OwlMind BotBrain
4. Customize your OwlMind BotBrain

### (Step 1) Configure your Discord Bot 

Follow the instructions at: [How-to Configure a Discord Bot with OwlMind?](docs/discord.md)

Save the TOKEN that you will create thought this process; we will use it in Step 3.

### (Step 22) Install OwlMind locally

Clone source from GitHub:

```
$ git clone https://github.com/GenILab-FAU/owlmind.git
```

If you have 'gh' installed (https://github.com/cli/cli)

```
$ gh repo clone GenILab-FAU/owlmind
```

### 3. Animate your Discord Bot with an OwlMind BotBrain

(3.a) Setup the Discord Bot TOKEN
* Get the TOKEN you created in (Step 1)
* Create a .env file like:
```
# .env file
TOKEN={My Token}
```

Alternatively, you can hard-code the token within bot-1.py

```
# bot-1.py

(...)
if __name__ == '__main__':
    (...)

    ## Alternative: Hard-code your TOKEN here and remote the comment:
    # TOKEN={My Token} 

    (...)
    # Kick start the Bot Runner process
    bot = DiscordBot(token=TOKEN, brain=brain, debug=True)
    bot.run()
```







## Understanding

<img src="docs/images/owlmind-arch.png" width="200">







