Language: Englishi | [简体中文](README.md) | [繁体中文](README-zh-tw.md)

# How to answer questions The smart way

[![](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square) ![](https://img.shields.io/badge/License-CC-blue?style=flat-square) ](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)![](https://img.shields.io/badge/Written%20with-❤-red?style=flat-square) <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

**How to Answer Questions The Smart Way**

This document serves as a reference for a logical way to answer technical questions from others, and Chinese version by Eltrac.

This is just a reference document, not any rules, I hope it will be helpful to you.

We are not responsible for any loss caused by yourself in the contents of this document, this is just a reference.

**Should note that this document is not specific to How To Ask Questions The Smart Way.**

Finally, welcome your valuable feedback and helpful Pull Requests.

Copyright &copy; 2020 Eltrac (BigCoke233) , All rights reserved.

## Contributors

Thanks to all the people who made contributions to the project!

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.guhub.cn"><img src="https://avatars1.githubusercontent.com/u/45323514?v=4" width="100px;" alt=""/><br /><sub><b>Eltrac</b></sub></a><br /><a href="#projectManagement-BigCoke233" title="Project Management">📆</a> <a href="#content-BigCoke233" title="Content">🖋</a> Raw Chinese Edition</td>
    <td align="center"><a href="https://scvoet.me"><img src="https://avatars1.githubusercontent.com/u/45708948?s=400&v=4" width="100px;" alt=""/><br /><sub><b>Scvoet</b></sub></a><br /><a href="#content-scvoet" title="Content">🖋</a> English Edition</td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

---

## Declaration

Before you read and adopt the body of this document, we must emphasize a few more points:

**This document is for reference only and is not a standard or rule of any kind.**

**We only provide content, do not provide any problem solving services, and are not responsible for any consequences.**

In addition, this document is a labor product jointly written by [Eltrac](https://github.com/BigCoke233) and other contributors. If you need to quote any content of this document, please indicate the address of the project after quoting , Otherwise it will be considered copyright infringement.

If you think this document helpful, I hope you can give us a star for support.

## Contents 

- Introduction
- Before answering the question
  - Ways to ask questions
  - Identify the questioner
  - Read the questions briefly
- When answering questions
  - In-depth analysis
  - Syntactic statements
  - Terminology
  - Pay attention to punctuation
  - Reduce rhetorical questions
  - Basic etiquette
- Necessary supplementary notes
- How to decline politely
- If the problem is still not resolved
- What to do if messed up
- Reward

## Introduction

A programmer will encounter various problems in the process of learning, and we will grow up in asking questions. One day, we will also actively or passively solve other people's problems. At this time, having the strength of technology does not mean that we can answer a question well. This also requires skill.

Recall how others answered your question. Among the responses to many of your questions, did you answer questions that were not asked, the sentences were incomprehensible, or were you unable to solve after a long time? If this is not the way you ask questions or do it yourself, then it must be that the person being asked is not very good at answering. Yes, it takes wisdom to answer.

If you lack the answering skills, you may make absurd mistakes unknowingly. This will not only waste your time, but will definitely waste the valuable time of the questions in solving the problem.

So how do you answer the questions of others efficiently?

## When answering questions

### Ways to ask questions

First of all, you need to confirm where you received the question, that is, to confirm the way the questioner asked you.

It may be asking for help on the forum, or sending questions in the group chat / chat room. Such questions are public-oriented and not targeted, so if you do n’t want to answer, you can just treat them as if you did n’t see them. At this time, you and the questioner are equal netizens / group members.

It may also be through the private chat window of the instant messaging software, email, face-to-face communication, etc. The question is only targeted to you (the person being asked), and the other party is mostly based on trust and respect for you. Ask you for help (of course, do not rule out the situation of emergency and medical treatment, this is not discussed here), then the other party directly asks you, but you should still treat each other with respect.

### Identify the questioner

The so-called "identity" here should include the following factors:

- Are you familiar (stranger / friend?)
- Do you have subordinate relationships (colleagues / leaders?)
- Questioner's technical level (Layman / Starter / Mastery?)

This is a more important factor. If you are familiar with the questioner, then you can try to recall the mistakes or bad habits often made by the other person and see if the problem is caused by these factors; if the other person is your leader or has a high status in the form To your people, then the tone should be more respectful, even if the other party is asking for you; if you know the technical level of the other party, we can decide whether to use more esoteric professional terms in the description, you can understand the other party Is there the ability to solve this problem and so on.

### Read the question briefly

Don't rush to solve it first, simply glance at the problem and see if it is:

- Very easy
- Able to be easily found answers for on search engines
- Already solved by someone
- Mentioned in the documentation provided by the original author if using an open source project

If this question does meet the above conditions, then you have every reason to not waste time and not answer the question yourself. You can tell the other party directly where the answer is, and maybe a link will help the other party solve the problem faster.

Of course, there is another important question that needs to be confirmed: **Is the other party capable of solving the problem under your description**. If this problem is troublesome, for example: you need to make changes in the source file, completely rewrite the code structure, and the other party has a weak foundation, then you can directly advise the other party to give up; if the situation is more urgent, you can also directly help Operate by the other party, using file transfer or remote control.

## When answering questions

### In-depth analysis

This is the most important part of answering the question. Now that you have decided to help the other party, then the other party is both a beneficiaries and a client. You need to take this matter seriously as your work. At this time, if it is a one-on-one request for help in a private chat, remember to send the other person a "Okey, let me see" and other words, indicating that you intend to help him to solve this problem.

First, answer an information technology related question. Most of the time you should know this information:

- Other's development environment and version
- Tools used by the other party
- Error messages (or logs) thrown by the program
- Actual and expected effects

You have to understand where the problem is. If it is an error, you should first understand the problem from the error information and logs, and then find the relevant source code. It should be common sense as a programmer. If the source code is correct and no error is reported, consider compatibility issues, pay attention to the environment and version, and if it does not take time, you may wish to re-implement it yourself to see if it is a bug or where a conflict has occurred.

As a programmer who can be asked questions, the basis is definitely no problem, and how to analyze the problem should not be said much.

But please note that after understanding the problem, it is best to read it again from the beginning to avoid misunderstandings due to omissions and omissions of jokes that are not answered.

### Syntactic statements

No matter how bad the l is, people will definitely speak it. As long as the solution is concisely described in clear sentences, it is concise and concise, and it is necessary to save the unnecessary parts. Also pay attention to the ambiguity of the sentence. Note that you are describing the solution, not writing a poem.

### Terminology

If the other party has a certain foundation, please use professional terms as much as possible. This will make the expression more accurate, concise and powerful. At this time, you don't need to think too much about whether the other party understands the word correctly, just make sure you use the word correctly.

If the other party has a certain foundation, please use professional terms as muSometimes there are multiple expressions of the same thing. For example, an Chinese dog can be called both a dirt dog and a Chinese Garden Dogt. At this time, we should try to choose a vocabulary that can be quickly understood by the other party, which is usually a more popular expression. "Dirt dog" are more commonly used than "Chinese Garden Dog". But when you want to use them, selecting "Chinese Garden Dog" will make the expression clearer.

When necessary, use English nouns to express their meanings more accurately, because many nouns are translated from English, it will inevitably cause ambiguity, such as the Flex layout in front-end design, and not many people will use it Call it "flexible layout". Not only can English be used more accurately, but it can also be more concise and clearly.

### Pay attention to punctuation

Many ambiguities are caused by punctuation. Think about why there is such a "functuation". You don't have to use every punctuation mark in a sentence with 100% accuracy. You just need to ensure that this sentence is not understood by others. You can even use only commas and periods in a sentence.

If you really hate punctuation and annoying, and find it difficult to switch input methods just to type the correct symbols, why not try to replace them with spaces or newlines? Although I do not recommend this approach.

### Reduce rhetorical questions

Many questioners do not understand the wisdom of asking questions. They do not always give complete information for the questionees to analyze, and often they need to ask them in turn to get more information. I think this is why many GitHub repositories set a default format for submit issues, just to make the questioner provide as complete information as possible.

You will also encounter times when you need to ask back, but in many cases this is very time consuming, because questioners with poor foundation often need you to explain to them what and where you want the information, and the other party may also Finding the answer while waiting for your answer is not friendly to the other party. Therefore, it is necessary to reduce the number of cross-examinations as much as possible. If possible, speak out the information that the other party has not provided, which is friendly to both parties.

### Basic etiquette

Although the other party is asking for you, you'd better treat the other party equally and respect each other. You don't need to pay special attention to the use of honorifics, because from a certain perspective, the person you should be respected is not you, but you should not belittle it, even if it is a joke.

Please avoid saying "Will such a simple question?", "The answer is obvious". In this case, if you do not know how to express it euphemistically, you can directly give the other party the URL of the relevant information for him Find the answer, not a taunt.

After solving the problem, you should also respond to the other person's thanks in a timely manner. It should not be difficult to say "no thanks" or "trivial"? If the other party has caused some trouble in the process of asking for help because of their weak abilities, they should also apologize and respond in a timely manner. These gratitude words are not listed one by one.

There is no need to talk about etiquette, anyway, just do it.

## Necessary supplementary notes

Sometimes, after the problem is solved, it will cause some other small problems, especially temporary solutions to bugs in certain programs. You need to explain this clearly, so as not to bother the other party to find out and ask again.

After some functions are implemented, the related code needs to be changed frequently in the future, and it should also be explained clearly.

In short, if the other party needs to pay attention, please help to the end, and don't cause other troubles to others due to the negligence of explanation.

## How to decline politely

When you receive a question from another person, you may be busy, or you are unwilling to answer or help because of a bad mood or other reasons, or you may not be able enough. What you have learned is not related to that aspect and cannot be answered. It should be **rejected**.

First of all, truthfully explain the reason why you ca n’t answer (if this reason involves personal privacy, you can use the universal “I ’m busy”), and it ca n’t seem too perfunctory. Who knows how the other side secretly commented on you?

If possible, you can recommend other capable bosses, or websites / documents that may have relevant information, so that the other party can find a direction and solve the problem faster.

Finally, although there is no need to apologize, please say "I'm so sorry".

## If the problem is still not resolved

The solution provided by your analysis of the problem may not necessarily solve the problem. There are many reasons for this: the execution error of the other party, the problem of the solution itself, the unsolvability of the (probable) problem, etc. But don't give up until you find a way out.

Do it yourself, re-implement by remote control or set up an environment yourself, this method can effectively solve the problem that can be solved. Depending on your own approach, you may be able to easily find the loopholes and errors of the other party, but note that this method is limited to the last resort, otherwise it is cumbersome, time-consuming and prone to accidents. It's just effective, not efficient.

If that doesn't work, try to find the problem in subtle ways. For example, problems such as local caching are very simple and you should pay attention to them from the beginning, but maybe you missed it. In addition, restarting and reinstalling is also a method you should try long ago.

If in the end you still can't help the other party to solve the problem and waste the other party's time, a "sorry" is always good. Usually this kind of problem is already difficult to find the answer on the search engine or some websites, you can recommend some more powerful guys to the other party, maybe someone else will solve it?

## What to do if messed up

If you describe the solution or directly help, due to operating errors and other reasons, the other party caused some losses, such as: data loss, server overload and other problems. Although this situation is less common, you should take responsibility if you encounter it.

First and foremost, should say "I'm sorry". In this case, the first thing you can do is **apology **, take the initiative to admit your mistake, describe the reason for the accident, and don't make the other person think you are joking.

Then, try to remedy. Just like when you accidentally broke the toys of other children's children, no matter what the result, you still have to repair the error. Even if you can't completely repair it, the way still showing your attitude.

In the end, if it really caused irreparable losses to the other party, how to compensate depends on the other party's thoughts.

## Reward

You helped the other person solve the problem and deserve a certain amount of compensation. But in the Internet, it is more of a kind-hearted help. You should n’t ask for compensation forcibly. Don’t think that if you help the other person to do a little favor, the other person should give your money, not to mention that the money is not much. However, if the other party really wants to use money as a thank you, don't decline, because this is what you deserve.

---

&amp; Copy; Use [BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/ded.zh) for authorization.
