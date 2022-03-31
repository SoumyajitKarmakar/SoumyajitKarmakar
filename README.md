- 👋 Hi, I’m @SoumyajitKarmakar
- 👀 I’m interested in computers and guitar
- 🌱 I’m currently learning meditation
- 💞️ I’m looking to collaborate on machine learning projects or a bit of game dev
- 📫 How to reach me, use karmakar.soumyajit@gmail.com

Hi @ChrisCummins,
I would like to take a shot at fixing this problem.
I have a question and a trivial solution which might be very silly, but if this

>env.reward_space = "Foobar"

>env.reset(benchmark="benchmark://foo-v0/abc")

already works, then why not just add a new argument in the function and put the first line in the function body ? Something like,

>def reset(..., reward_space: str = "same",...):

>      if reward_space != "same":

>        self.reward_space = reward_space

and then copy the rest of the function below it, and let it run its normal course of actions.

<!---
SoumyajitKarmakar/SoumyajitKarmakar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
