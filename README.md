# AutoIssMemeCoins
Code for automatically issuing MemeCoins to MemeAlerts users for channel points on Twitch

If you want to give MemeCoins to your viewers for channel points, but you can't always do it manually, then the prepared code will help you automate the whole process.

# How to Install
1. Download the [Streamer.bot](https://streamer.bot/downloads)
2.  Log in and connect your Twitch account
3.  Actions & Queues -> Actions -> Add New Action\
   ![Add-Action](https://wenjiro.vmxe.ru/img/s1.png)
4. Add Trigger (Reward Redemption)\
   ![Add-Trigger](https://wenjiro.vmxe.ru/img/s2.png)
5. Create new Reward\
   ![Create-Reward](https://wenjiro.vmxe.ru/img/s3.png)
6. Add Sub-Action:\
   a. Target Info (%rawInput%)\
   `Add -> Twitch -> User -> Get User Info for Target`\
   b. Set Global (bearer, coins, streamerId)\
   `Add -> Core -> Globals -> Global Set`\
   **bearer** - bearer code of your MemeAlerts account\
   **coins** - the number of MemeCoins that you want to give out for receiving a reward on the channel\
   **streamerId** - ID of your MemeAlerts account\
   c. Add Reward Get Info and choose your reward\
   `Add -> Twitch -> Rewards -> Get Reward Info`\
   d. Add Execute Code\
   `Add -> Core -> C# -> Execute C# Code`\
   You can get the code [here](https://github.com/wenjiro/AutoIssMemeCoins/blob/main/code.cs)
7. Add References
    - System.Net.dll
    - System.dll
    - Microsoft.CSarp.dll
    - System.IndentifyModel.dll
    - System.IndentifyModel.Selectors.dll
    - System.IndentifyModel.Services.dll
9. Compile
10. **You Great!**


Мемкоины за баллы канала Twtch, MemeCons for Twitch Rewards
