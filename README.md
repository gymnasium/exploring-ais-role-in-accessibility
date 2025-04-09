# Exploring AI’s Role in Accessibility

with [Aaron Gustafson](https://www.aaron-gustafson.com/about/), of Microsoft

Recorded on Wednesday, April 2, 2025, at 12PM EDT

- [Watch the Recording](https://www.youtube.com/live/7ObB4jM-QXU) on YouTube
- [Explore the Resources](#resources)
- [Read the Transcript](#transcript)

## Resources

- [Gymnasium](https://thegymnasium.com)
- [Modern Web Design](https://thegymnasium.com/courses/modern-web-design/)
- [AI and speech technologies](https://www.youtube.com/watch?v=5FWwM1S8RfE) (video)
- [How to Use Seeing AI - Assistive Technology Tip](https://youtu.be/T0mE8SF-wbs?feature=shared&t=368) (video)
- [The Prompt with Trevor Noah](https://www.microsoft.com/en-us/research/group/ai-for-good-research-lab/the-prompt/)
- [Global Symbols](https://globalsymbols.com)
- [Opportunities for AI in Accessibility](https://alistapart.com/article/opportunities-for-ai-in-accessibility/)

## Transcript

**Jeremy Osborn:** Good morning, afternoon, evening, whatever it might be for folks joining us. Thank you so much. My name is Jeremy Osborn. I am the director of learning for Aquent Gymnasium.

I’m here with my colleague Andrew Miller, who is the program director of Gymnasium. And we are joined by a guest, Aaron Gustafson. And we’ll get into a little bit more about what he does in just a moment.

But we’re really grateful to have everyone join us. We’re going to be talking a little bit about the role of AI in accessibility. And this is one of our — how many livestreams have we done, Andrew, exactly?

**Andrew Miller:** Oh, wow. That’s a really good question. More than a few.

**Jeremy Osborn:** Yep. That’s the correct answer. We have done more than a few. [LAUGHS]

**Andrew Miller:** Yeah, we’re data driven.

**Jeremy Osborn:** Yeah. And a lot of the stuff that we have talked about in the past has been — I mean, we’ve covered a lot of subjects, but of course, AI has been on a lot of people’s mind and radar. And I think we have the pleasure today of talking to Aaron about some of the aspects of AI that maybe we don’t think about on a day-to-day basis when we’re seeing like, cool, goofy images populating our social medias.

Today, we’re going to discuss some of the ways that AI is making a meaningful difference for people with disabilities or impairments. And that’s going to range across the board from things such as generating alt text for images, voice preservation and recognition, text transformation, all sorts of things.

Aaron, first of all, welcome to our little livestream here.

**Aaron Gustafson:** Cozy little livestream.

**Jeremy Osborn:** Yep. Cozy.

**Aaron Gustafson:** Thank you so much. Thanks for having me. It’s like a return to port for me because — let’s see. In 2000, I think, I worked through Aquent for a little while, so.

**Jeremy Osborn:** Yeah, that’s right. And not only that, we should mention — that’s true. I remember we discussed that. That’s almost a quarter century ago. Just saying.

**Andrew Miller:** Isn’t that wild?

**Aaron Gustafson:** I’ve earned all this gray.

**Jeremy Osborn:** [LAUGHS] And we should also mention that we run a free online course platform called [Gymnasium](https://thegymnasium.com). That’s kind of what we do. In addition to these livestreams. Aaron also is one of our first instructors. And we can talk a little bit about your background. But you kind of started like in web development and web design back in the day. And you did our course [Modern Web Design](https://thegymnasium.com/courses/modern-web-design/), which is —

**Andrew Miller:** One of our most popular classes. That is still one of our most popular classes.

**Aaron Gustafson:** It’s almost 10 years old now. I think we’re probably due for an update soon.

**Jeremy Osborn:** Yeah, we are. We try to make it as evergreen as possible. But I don’t know. I think you did a pretty good job of —

**Aaron Gustafson:** I intended for it to be pretty timeless — more philosophical than here’s the cutting edge things. But yeah.

**Jeremy Osborn:** And so I don’t if I mentioned at the beginning. Again, your official role is — make sure I’m going to get this right — principle accessibility innovation strategist at Microsoft. Is that correct?

**Aaron Gustafson:** Yep. Yep, that’s correct. I think officially in terms of career track, I’m a technical program manager. But yeah, principle level. And I get to focus on accessibility innovation both internally and externally to Microsoft, which is a lot of fun.

**Jeremy Osborn:** Yeah. And I’m kind of curious if you can expand on that a little bit. I know that again, your core skills kind of started off as web development, I guess it’s fair to say. But yeah, we’re going to see that if captions can. We had a question from our LinkedIn users.

**Aaron Gustafson:** They should be.

**Jeremy Osborn:** They should be. But Roman maybe behind the scenes can track that down. It would be good to get captions enabled here. So yeah, so your day-to-day — I think when we had a call a couple of weeks ago, it’s kind of curious. Like, what in general do you end up doing, and some of the things that you are responsible for having to do with all things AI and accessible?

**Andrew Miller:** I seem to remember when we asked you, “So you’re involved in a lot of things, so what is your day-to-day?” And I think that was literally the phrase. And when you were done with that inventory of things, that sounded more things than would fit into 24 hours.

So you might be the busiest person. You probably are, but you’re but you do have — you’re involved in a lot of very important work that’s going on in and around the Microsoft sphere. So yeah, definitely tell us all the things.

**Aaron Gustafson:** All the things. So my role is kind of a unique one in that I get to work on a lot of just really amazing and impactful projects. I have been working a lot over the last year and a half with Team Gleason, which is an ALS support organization, to investigate creation of synthetic voices.

So a lot of times when we think about AI created voices, we think about deepfakes. There’s been a lot of, obviously, news about that. But what we’re looking at is actually, how can people consensually create a copy of their voice for using when they no longer have use of their natural voice?

So with ALS, eventually a lot of people are robbed of their voice. As they lose control of their vocal cords, they get dysarthria, it becomes harder to understand them. And so they need to rely on AAC software, which stands for augmentative and alternative communication.

So if you see symbol boards that people can compose sentences on, and then it gets read out for them, how can we bring a natural sounding voice clone to that experience so you can continue to show up as yourself and to continue to have your personality, to have your loved ones continue to be able to hear you, as opposed to hearing you sound like a computerized voice like we all were kind of used to hearing Stephen Hawking and stuff like that? Eventually that became his voice, right?

But for most of us, our family kind of grows up around us. Our kids learn to hear us how we are. And if all of a sudden something happens like you get ALS or throat cancer — we’ve seen that happen with Val Kilmer — lots of things can happen that can rob you of the use of your voice, even in the short term.

I mean, if all of a sudden you have laryngitis and all of a sudden you can’t speak, how can we enable you to continue to communicate as the authentic you in that way? So that’s been something I’ve been exploring with Team Gleason. We ran a pilot with them to provide high quality synthetic voices using some of the Microsoft technology for this. And the reaction to that was tremendous. It was really impactful for folks. I think you’ve got a video that we want to show in a minute. But the work was really interesting. It was a lot of fun. Just amazing to see how people respond to it.

Also to think through the implications. What does this mean in terms of risk to people’s voices being stolen? Or how do we ensure that we do have the actual consent for somebody that they’re using their actual voice recordings? All of these sort of thorny issues. So that’s one area that I’m working in. I’m also spending a lot of time thinking about sort of the end-to-end picture of accessibility tooling.

So I come from a web design background, as you mentioned. So I’ve been working on the web since ‘96. And I’ve had a lot of experiences across the board in projects from planning stages all the way through to back-end development and stuff like that. And all along the line, the truism about the cost of making changes the further you go into the product holds true. And that holds true for accessibility as well.

So it’s much more expensive to fix an accessibility bug in production than it would have been to catch it in planning, or design, or when you were coding. And so I’m looking at, what is the landscape of the software development life cycle? What are the touch points in there? And how can we, as Microsoft, improve on the experience our developers are having internally?

What could we potentially bring external? How do copilots, like what we see in VS Code, the GitHub Copilot and stuff like that, how do those factor in? What is the quality of the code in terms of accessibility that they’re producing? How can we improve that? So that’s kind of another aspect of what I’m doing.

A third bucket is I work — I’m on the advisory board for the Speech Accessibility Project, which is a consortium of different companies who were interested in gathering affected speech samples from a variety of — from people with a variety of different disabilities.

So the initial push was to work with people with ALS, with cerebral palsy, down syndrome, stroke, and Parkinson’s, and together speech data from them in order to train our speech recognition models to be better. And there have already been published results of improvements in that space, both from Microsoft and from Apple as well. And those are going to find their way into your daily products that you interact with.

So there’s already been improvements to the Azure speech recognition. There will be improvements coming to other products as well. As I mentioned, Apple’s been working on that. Amazon, and Google, and Meta are also part of that consortium. And so they’re doing a lot of interesting stuff as well.

So that’s kind of another piece. There’s a bunch of other things too, but those are kind of like three tentpole pieces that I’m working on currently.

**Jeremy Osborn:** Yeah. That seems like a lot for everyone. But yeah, so this is actually interesting. I mean, we’re going to show the video but the Team Gleason stuff. But before we do that, again, just from a high level because we have folks who, again, they join us. We talked about some of the processes behind AI and so forth.

So it sounds like there’s a large training component behind some of these things. And so, for example, for the Team Gleason, is it fair to say that there’s a training process that takes time, where you have the ability to record an individual’s voice? And then I’m just curious. How does it work?

**Aaron Gustafson:** So in terms of the synthetic voice creation, the process varies based on the type of model you want to work with. So Microsoft has several different models. And every company’s models are a little bit different in terms of how much data they need to work with.

But the three models that we have, there’s the personal voice, which is almost a — we would refer to — some people refer to it as a zero-shot. I think of it more as a one-shot. You record a statement giving permission to create a synthetic version of your voice, and then it creates a pretty good quality but somewhat lower quality voice. And that’s all it needed was that one statement.

Some only need — like the custom neural voice is sort of the umbrella that a lot of the Microsoft voices fall under. The Custom Neural Voice Lite model takes around 3 minutes of auto to create a pretty good quality voice.

And then there’s CNV Pro, which can take anywhere from 20 minutes to several hours. That’s the one that tends to get used for — at least traditionally tends to get used for things like professional voiceovers and stuff like that, where let’s say you need to get high quality samples, you want to generate more emotionality in the voice, you need to be able to rerecord some dialogue or something like that, or some overdub, or you’re using you’re creating a brand voice and you’re hiring a voice actor to create a brand voice and you need to be able to use that without having to call that person into the studio. That’s where CNV Pro tends to come in.

But that was actually — the CNV Pro is what we used for the folks at Team Gleason when we were working with them. But it’s pretty amazing. I mean, I’ve seen — we had a gentleman that we worked with who has ALS, and we were able to take some recordings that he gave us that were really, really poor quality recordings from WhatsApp voice notes that he would send to his colleagues.

**Jeremy Osborn:** Oh, interesting. OK.

**Aaron Gustafson:** And I think we only had somewhere around like 70 or 90 seconds of audio. And we were able in — he’s in Argentina, so in Argentine Spanish. And we were able to create a voice for him.

We didn’t even have a Argentine Spanish base model, so we had to go with the closest geographically. So we had to go with the Mexican Spanish one, which was not ideal. So some of the words are mispronounced or sound like he comes from a different region in Argentina. But overall, he was really impressed with how accurate the voice was to his actual voice pre losing the ability to speak.

**Jeremy Osborn:** Well, I think I have that queued up as a screen share, but I need our administrator, Roman, if that’s possible, for you to share that with our audience. And so again, this is on YouTube here. An example of how Team Gleason helped use the Azure custom neural voice. And let’s —

**Aaron Gustafson:** Yeah. This is Brian Jeansonne, is his name.

**Jeremy Osborn:** Brian Jeansonne. OK, great. Thank you. All right, so I’m going to just go ahead and play this. This is about 3 minutes and 53 seconds. So we’ll go from here. And if someone can just confirm that the sound is coming through, that would be great too. So here we go.

Video: [AI and speech technologies](https://www.youtube.com/watch?v=5FWwM1S8RfE)

> Learn how an ongoing pilot with Team Gleason helped Brian Jeansonne explore what an Azure custom neural voice can do to bring more of his personality into everyday conversations.

[VIDEO PLAYBACK]

[GENTLE MUSIC]

Kristy Jeansonne: Brian is somebody everybody should know. He’s just witty, and funny, and likes to tell a lot of jokes. A lot of dad jokes.

Brian Jeansonne: I used to bite my nails. But thanks to ALS, I don’t anymore.

My name is Brian Jeansonne. I was born and raised on the outskirts of New Orleans. I married my amazing wife in 2003. We have created a beautiful family of seven.

Kristy Jeansonne: Around 2019, Brian started having some issues with his ankle. I was able to get him an appointment with a doctor and he was like, I hate to tell you, but this is ALS. We were just — we were definitely not ready. Like, my heart hurt for him being so caught off guard.

Blair Casey (Executive Director, Team Gleason): For those people who have experienced ALS, you don’t wish it on your worst enemy. It’s a neurodegenerative disease that essentially stops sending signals from your brain to the rest of your body, to the point where you lose your ability to use your arms, or your legs, your voice.

Brian Jeansonne: My voice was my superpower. I am a conversationalist. So my voice weakened over a year’s time, and the whole year was filled with sorrow.

Emily Kornman (Lead Technology Specialist, Team Gleason): We might joke like, oh, I hate the sound of my own voice. But in reality, your voice is your personality. It creates an actual emotional auditory event in the brain of your loved one.

My voice was the scariest thing to lose more than eating and even breathing, because I knew there were fixes for those things. But my voice? How would I live in a world where my kids wouldn’t be able to hear me say I love you?

Blair Casey: Over the course of somebody’s progression, one thing that they can do to be proactive is preserving their voice.

Emily Kornman: One of the challenges with voice banking in and of itself, because it creates that computerized version of their voice, is that it doesn’t have a lot of emotion and tone. So with what Microsoft is doing, their voice banking technology really gives someone back that intonation and a little bit more of their personality.

Kristy Jeansonne: There’s just something intimate about hearing his voice, his little quirks.

I’m just excited to really just hear him.

Brian Jeansonne: Any technology that can get my voice as close to normal, well, that is a gift not just to me, but to my whole family.

Emily Kornman: So, Brian, today we’re going to play a newer version of your voice. And I’m hoping when you hear this, and when you hear this, it’s going to remind you a little bit more of what he sounded like beforehand. So you just choose any phrase, and then I’ll play it on here as well.

Brian Jeansonne: Hey, beautiful people. I am so happy to be with all of you.

Emily Kornman: All right, I’m going to type it out.

Brian Jeansonne: Hey, beautiful people. I’m so happy to be with all of you.

Kristy Jeansonne: Dang!

Brian Jeansonne: Hey, Kristy, I love you.

Kristy Jeansonne: Oh, my goodness. I can’t believe that, really. Like, that’s really crazy. [CHUCKLES]

Blair Casey: The biggest opportunities when it comes to emerging technologies is the gap that it can fill, not just here for people with ALS. But you think about anybody whose speech is affected, AI has the ability to increase communication, increase independence. It’s the next wave for accessibility.

Emily Kornman: Here at Team Gleason, we have a phrase, no white flags. From my experience working with individuals living with this disease, that really means that they will not give up who they are.

Brian Jeansonne: I am completely in awe and amazed by this voice. I think this sounds just like me, and I am overwhelmed with joy that my family gets to experience this part of me. In many ways, I feel like I am back.

[END PLAYBACK]

**Aaron Gustafson:** I can’t tell you how many times I have watched that video and it still gives me, like, tingles and chills.

**Jeremy Osborn:** Oh, yeah. Let me turn that off. Amazing. I mean, yeah. I’m agreeing with all of these comments, Risking and the LinkedIn one.

**Aaron Gustafson:** Exactly. No, it’s phenomenal. I mean, some of the people that we’ve worked with, there is a — so Brian used to be a preacher, and so his voice was his superpower, absolutely. And so thankfully we had recordings of him before he lost use of his voice. But a lot of people, they don’t have recordings from before, or they don’t have that many.

And when you’re diagnosed with something as major as ALS, there is so much to deal with. Historically, to create an honestly fairly poor quality synthetic version of your voice using last generation of technologies, you would have to spend hours recording. And it’s exhausting, especially if you are — let’s say you’ve already lost some of your mobility, your ability to use a mouse or something like that. So having to use the computer with your eyes is very, very tiring.

And having to go through the process of recording your voice, it would just — it would wear you down. And a of people, not to be a downer, but there were a lot of people who would be in the process of trying to record their voice and they would transition without ever having done that.

And so the fact that we can help people to create their synthetic voices — and high quality synthetic voices at that — in just a few minutes of their speech that they might be able to take from a voicemail that they left their loved one or something like that is just incredibly powerful. So it’s been amazing to get to work on that project.

In addition to the pilot, I’m continuing to work on some other stuff with Team Gleason to try and really democratize access to this sort of technology for people who have ALS, and then eventually people who have other sorts of progressive speech disorders.

**Andrew Miller:** So what are some of the ways that you’re doing that to get access to the accessibility?

**Aaron Gustafson:** So one of the things that I’m doing with them — and we showed this off a little bit at the ASHA conference, which is a conference for speech language pathologists and folks who kind of work in the speech space — is Tim Gleason will be releasing a dashboard initially for just their users, but they have some goals of turning this into an open source project that other organizations would be able to stand up on their own.

But if I were to be a new client of Team Gleason, I could totally self-serve making my recordings. All of my recordings get stored in a location that I control. So Tim Gleason does not have your recordings. You keep those. And then you decide what voice vendors you want to use.

And we’ve already talked to a couple of different AI voice vendors about participating in the dashboard. And so you’ll create the recordings on your own time, you’ll have complete control over them, and then you’ll be able to decide which vendors you want to try. And if it doesn’t work out with a particular vendor, you don’t like the voice you get, you can try a different one, or you could try several at once.

But ultimately, the individual is in charge, and they control their privacy, and they control who has access to what and when they allow somebody to access essentially their biometric data, which is what their voice is.

And then simultaneously, we’re trying to figure out, how can we work with — some of the voices already have playback in some of the common AAC software. But how can we work to expand that ecosystem as well?

As I’m sure some of you know, a lot of the voice models that are out there — these high quality AI ones — are cloud-based. And that is problematic for people who might have limited connectivity or people who might have limited connectivity throughout the day. So really making sure that we can find ways to securely enable them to have an offline voice model that can continue to operate for them but still be secure and private. So it’s some thorny challenges, but definitely important work.

**Jeremy Osborn:** And just for some of our less — maybe not — less tech savvy folks. So when you say some of the voice data is in the cloud, does that mean it’s having to request or process the voice translation over the web? It’s not like —

**Aaron Gustafson:** On a remote server. Yeah. Yeah. A lot of them, a lot of the voices, even some of the ones that we offer, like I mentioned.

The personal voice one, that is a purely online model. That one is not available offline. Some of the custom neural voice models are able to be run offline. So that’s an option. And then I know other vendors, like [Acapela](https://www.acapela-group.com), have offline voice models as well that can be stored and run locally on your machine.

**Jeremy Osborn:** OK. Yeah, I guess I’m kind of curious.

I mean, some of the — as Andrew and I have been kind of tracking this the last few years and trying to understand where things are going, I think one of the things that kind of obvious to anyone who just follows the general field of AI is that these rapid advancements that we’re seeing — these huge quantum leaps in like, wow, this thing can now do this that only six months ago could do that.

And so I’m curious if — and maybe this will apply as a broader question that applies to some of the other examples we’ll look at. Do you feel like this is the same trajectory that we’re seeing in, for lack of a better word, this accessibility space? Like, are we seeing these kind of —

**Aaron Gustafson:** Yeah. And honestly, so I would say on the whole I am — or at least when I came into this role, I was very much an AI skeptic. And I still remain very skeptical about AI. And I think a lot of that is due to the demos that are out there are just not super compelling from a societal standpoint. I see so much risk to what’s being done out there in terms of spreading misinformation.

It’s sort of like I look at AI now and the ubiquitous access to it, or near-ubiquitous access to it, a lot the same way I look at how the web kind of came about. And the web was kind of really good in some ways and really not so good in other ways.

So the low barrier to entry to creating a website just gave voice to so many people to share their experiences, and for us to all learn from them, and really just democratized access. But at the same time, it provided those same sort of tools to people who wanted to act in bad faith, or who wanted to spread propaganda, or misinformation, or biased opinions about groups of people, and that sort of stuff. And it enabled them to find each other and mobilize as well.

And I feel like the amplification that the web provided and search engines on top of the web provided is even more built up in AI because so many of the language models and such are trained on information that they found on the web with zero vetting of the quality of the content that was going in.

We’ve got that age old concept of garbage in, garbage out. And so without proper tuning and guardrails and such, we see a lot of the biases that exist in the data sets that drive these models being amplified by the models themselves.

And so I think it doesn’t mean the models are worthless. It doesn’t mean that there’s not value there, that there’s not stuff that these models can do really well. But we have to be really thoughtful about how we approach them.

So if you’ve sucked in a bunch of data that is, say, biased against people who are deaf, for instance, then the model is going to mirror that and amplify that. I’ve heard examples from people where they start off a conversation with a chatbot like, I’m blind and I need to know how to do x, y, or z. And the chatbot would respond with, “I’m sorry to hear that,” and then try and help them solve their problem.

And that’s really diminishing, right? Like that’s not how — like, that’s just a fact. You don’t need to give you an opinion about that. You can just move on and help them solve their problem that they actually came to you for.

And we see these same sorts of biases show up in image creation models where there’s not a lot of training data around disability objects. So if you asked it to show you what a braille touch feedback device looked like or something like that, it’s going to be all over the place or it may not do it.

One of the examples that I show folks a lot is if you ask for an image of a blind person, almost invariably, that person is blindfolded. And if they are shown with a cane, I’ve seen them shown with hooked canes that come up to their hip, as opposed to what we would traditionally see as a white cane. Those sorts of things.

And it’s not that these models are bad, but they just don’t have the data to be able to do these things right. And so it’s really important that we think about the inputs that go into these models, make sure that they’re representative of people with disabilities, which is why the Speech Accessibility Project exists.

But we need those same sorts of things for other kinds of data as well. We need to make sure that disability data is included in the data sets that are training these models, whether they’re language models, vision models, computer vision models being able to go around and recognize objects.

So we often think about the computer vision models. The early ones that we would see on the web were like, is this a hot dog or is it not a hot dog? Those sorts of things, right? But a lot of those vision models were taught to identify a hot dog.

Maybe it’s slightly skewed, but it’s in isolation against a white background, as opposed to a hot dog that maybe somebody who is blind is holding their mobile device and they don’t have it fully in focus. They don’t have it — their device might be moving and so it might be blurry. It’s not going to be centered. There’s going to be a lot more going on.

But if you’re helping somebody find their food, find their keys, find their purse or their backpack — which are all things that people who are blind and rely on these devices do — we need to make sure that they can recognize those devices and tell them where they are. So we need to train them how to recognize blurry images, images that are only a portion of an object, or something of that nature.

So we need to be really thoughtful about this, and honestly, cast as wide a net as possible for the types of data that we’re bringing into these models to make sure that they’re able to actually realize their full potential.

**Andrew Miller:** The one thing that you mentioned, Aaron, was the bias that’s in inherent in the training that’s inherent in the models.

Sort of an everyday sort of experiment you can do is just have any one of these image generation platforms produce, like, show me a successful executive. Or just show me a lawyer, show me any role. And just take a look at what does Firefly produce, versus ChatGPT, versus Gemini, etc.

And the biases, they’re right there. You can see it’s like oh, OK. Only people of a particular — who look a certain way could possibly be successful executives. And that’s the — I mean, eventually that will get watered down hopefully, and so that it’ll be more fair.

One thing that you mentioned, though, that you had told us about this application that we had raced off to install on our phones and checked it out, and it was absolutely fantastic seeing AI. And we’ll share some links at the end, but the application is incredible.

And so here I am, holding the phone without any difficulties, without any challenges. And I’m pointing at things, and it’s telling me what I’m seeing, and how many people, and how close. And it’s mind-boggling. And I didn’t even think about how much work it must have required to be able to do that in, shall we say, atypical circumstances where maybe someone has a tremor and the photograph is going to be blurry or the camera’s not going to be held straight.

And one of the features that I was thinking about — and I’ll call this out as my own ignorance. I don’t really know. One of the things it’ll do is it’ll read a label, which I think would be really cool if you’re in a store and you need help to figure out what this product is and what’s in it.

Are the UPCs in the same place on every product? How would you know? So you would basically just hold the object up and move the phone around until it identified the place for that?

**Aaron Gustafson:** Yeah. And some of the models, I mean, depending on the model that you’re using, they may read the label itself. They might read the UPC code or a QR code that’s on it.

There are some that have been trained to recognize the packaging as well, so that you don’t even need to pull something down from the shelf. You could just scan along the shelf and see what certain things are. And some folks might be familiar with that from some online shopping experiences and stuff, where you could take a picture of something and get the price of it.

So the technology is definitely advancing in terms of that to be able to help folks figure out what is the product I want to pull off the shelf, is my hand next to it, that sort of thing. Yeah.

**Andrew Miller:** Yeah. That application made me realize just how liberating this technology is for people. I can’t imagine being shut off from one of my senses. And to be able to regain some aspect of that through technology would be incredibly empowering.

**Aaron Gustafson:** Yeah, and that’s the [Seeing AI](https://www.seeingai.com) app.

**Jeremy Osborn:** Yeah, and I actually have — I have an example of that loaded up. We can actually watch that again.

So this is actually what I found. This is from an organization, the [Foundation for Blind Children](https://seeitourway.org). And so this gentleman — and I’m sorry, I don’t know his name. I kind of skipped ahead. He is about to kind of demo this one example. So let’s just quickly do that.

And you’re seeing on the left the application itself. And then on the right, obviously someone is filming him as he’s doing this.

Video: [How to Use Seeing AI - Assistive Technology Tip](https://youtu.be/T0mE8SF-wbs?feature=shared&t=368)

[VIDEO PLAYBACK]

Seth Leblond: Much more clearly.

Seeing AI: Gentle. Take Picture button.

Seth Leblond: And for Handwriting Mode to work, we just get ready with our Take Picture button. We double tap.

Seeing AI: Processing. A sunset pictorial.

Seth Leblond: It actually said, “A sunset pictorial.” Good information. I’ve also been successful in using Handwriting Mode to read very low contrast items like credit cards.

That wraps up our six —

[END PLAYBACK]

**Jeremy Osborn:** Obviously, this was not a full demo, but that was just a quick little taste of the app. And again.

**Aaron Gustafson:** There’s a really great video with Saqib, who is one of the creators of Seeing AI, and Trevor Noah that I can grab the link for and drop in. But I think it’s “[The Question with Trevor Noah](https://www.microsoft.com/en-us/research/group/ai-for-good-research-lab/the-prompt/),” or something like that. I forget what the name of his show is.

But yeah, he has a really good interview with Saqib, and they use it on the set that they’re on. And Saqib shows off some of the functionality of Seeing AI. It’s really impressive. I mean, being able to pick out matching clothes from your closet, being able to do all sorts of things like that.

The amount of independence that it enables people to have is pretty substantial and just keeps getting better. And to me, that’s ultimately I think the really interesting thing.

And really, the thing that really drives me every day is not so much thinking, how can we empower people, but how can we give people the tools to empower themselves? Because ultimately, they should be in control of their own lives. Like, they don’t need us.

I feel like that really does align with Microsoft’s mission, which is why I feel like this is the right place for me to be, because we are about helping people to achieve more and to do what they want and need to do in their lives. And so that really aligns with the work that I’m doing, I feel like.

**Jeremy Osborn:** I should have mentioned this at the beginning, too — just some housekeeping. We’re going to save like 10 minutes-ish towards the end for audience questions. And right now, the way we’re set up here, we are broadcasting this in a few places. We can only see the ones that are coming in from LinkedIn.

So we do have a couple questions that came in and we’ll try to get to those towards the end. But please, just kind of — if you have running thoughts, comments, just throw them into the chat. Again, only on LinkedIn at this point. And then we’ll try to cover those as best as we can.

Yeah, so another — yeah. I mean, in a way — so some of the questions that we’re seeing here just related to what you’re talking about earlier, about this idea of bias. And we know that these are, as Andrew mentioned, these are things that we can see in generative imaging.

And I had an opportunity to sit in on a — we had a chat about the impact of LLMs and AI on things like the environment, and electricity, and all that. I’m kind of curious. To me, it seems clear to me — the views and opinions of this are mine only at this point — but that the benefits of some of the costs that we’re seeing that maybe are not so obvious when you’re creating this stuff seem obvious when you’re creating things that improve in general the society.

But I’m curious. I know that you had sent us some link to some of the responsible AI principles. In general, what are your thoughts on things like that, some of the hidden costs? To me, it seems worth it, but —

**Aaron Gustafson:** Yeah, I think a lot about this. And I think especially as I’m looking into this space of accessibility tooling, and how can we improve the accessibility of our products in a better way so that we’re basically instead of — trying to use an analogy here. Or, not using analogy — an example.

But let’s say you have an accessibility issue in your website. The contrast is too low, for instance. Somebody might have a plugin. Or eventually, since people are AI-ifying everything, there might be some AI that’s adjusting the contrast, that feels very, very expensive to me.

Because then, if each individual person is having to hit that AI endpoint or whatever to be able to adjust the contrast to something that is appropriate for them, could that be found earlier and become less expensive to do?

Because if you’re changing it at the beginning of the process in the design phase of the software development life cycle, you’re catching it there. Not only is it less expensive to change because it’s cheaper to fix things earlier on in the project than it is later on in the project, but you’re only running that AI query once, as opposed to running it for each person in the world who might be visiting that site.

So in the same way, I think we need to think about when we’re using AI technologies. Where are we using them in the process? And is that the most efficient place to be using those? And how frequently are we jumping to that AI solution?

So some of the things that I’m thinking about are especially with this computer operation world that we’re starting to see, where you’re able to have an AI driving a computer. Phenomenally powerful. Really interesting concept especially for accessibility testing, which is just really challenging to scale.

When you’ve got maybe 100 different websites that you’re managing, or 1,000 different websites, or 4,000 different websites that you’re managing with hundreds to thousands of pages each, you cannot scale human accessibility testing across all of those places. So could models allow us to do that at scale? Certainly less expensively.

But what are the costs of that? So the costs of that are all the processing power, all the energy we’re having to use. Those models are not only interacting with the computer, they’re also doing computer vision, which is expensive. And there’s an orchestration of different things.

And there’s real — like, there’s money costs, but then there’s environmental costs to the energy use, all that sort of stuff that just kind of goes out from that. And we may decide that, yes, that is valuable. But is there a way to translate that into — or to produce an artifact out of the process of doing that that is then repeatable, that does not involve having to go back to the AI?

So just to throw out an example, if you have an AI go through an interface to accomplish a key task like booking a flight right on a website, could it leave effectively a paper trail of sorts that could be automated in Selenium, or Playwright, or one of those sorts of WebDriver-based tools that could then run it at much less expense on a local machine or something like that? That would be something that would ultimately be better.

Can we use a smaller model? Can we use a model that is local to the device? So like both the Chrome team and the Edge team are working a lot on local models embedded in your browser, making those available not just to websites but also to plugins.

So having the overhead of doing that cut down dramatically by — the work is not happening in the cloud, so there’s not the communication latency, there’s not the energy use of the communication, there’s not the energy use of the big model sitting somewhere in the cloud. It’s all able to happen locally on your machine on a very small and efficient model. Like, that seems like a really good direction to go.

Are we able to do the really expensive things once — like the creation of the synthetic voice — one time, and then move it to an embedded model that can be run much more cheaply on a local device so that we’re not having to do that communication to the cloud? Not only is it going to make a better user experience, but it’s going to be much more thoughtful in terms of how it is using the limited resources we have on this planet.

**Andrew Miller:** So I guess the key is in your intention, right? And to being thoughtful of these things because that’s the starting point. If it never occurs to you, that that’s not a concern, then it won’t be a concern.

And the lack of concern early on in your work then becomes — it cascades, and then it’s like it’s built in, just like bias and models. Just like, oh, we’ll get to the alt descriptions later. Right? And then it’s like, oh, well, maybe when there’s a lawsuit. Is that when you — is that a good time for you?

**Aaron Gustafson:** Even then, people pay to make lawsuits go away, right? They’ll settle out of court or whatever. But yeah.

And I think it really comes down to the experiences you’ve had that have shaped your perspective. I happen to have a very different experience of the web the first time I used it than most people, where when I was in school, we didn’t have the ability to use a graphical browser to access the web.

So I had to use a text-based browser the first time. And I went to a site that was all image maps. And I had no idea what that was at the time. But all I saw was literally in square brackets, image, image, image, image, image. And I was like, this web thing is BS, and I didn’t want anything to do with it. A couple years later, it ended up that being what I ended up doing for my career.

But that experience of being shut out really shaped my perception of how it is that we should be building for the world. I want to make sure that anybody who needs to use a particular tool, whether it’s to access their bank account, to reach somebody in their local government or what have you, that they have the ability to do so, and there shouldn’t be any barriers to them doing that.

And there are lots of people who love, love to put up blinders and say, oh, that’s not a problem. Like I’ve had somebody say — I forget what it was. Like, oh, we have no users who don’t have JavaScript turned on, for example, to use the web. And I was like, how do you know that? And he’s like, well, our analytics tell us.

And I was like, OK, tell me. Tell me about your analytics. What are you using for analytics? Oh, we’re using Google Analytics.

OK. Um, Google Analytics is JavaScript-based. So if JavaScript is not running, you’re not going to get that information. And they were just like, long pause. And people just — they don’t realize that they’re creating these artificial bubbles to live in that are not the real world.

And I think the more we expose ourselves to the experiences that other people are having, the more we can consider their experiences, and bring them into the process, and to make sure that they’re involved in the design of new tools, and new softwares that we’re building, and stuff like that. And I think the more we bring those diverse perspectives, I think the more we find really good, compelling use cases for the technologies that we’re creating.

So one of the questions in the chat was about, like, when is AI worth it? I think having AI draft your term paper is probably not a great use of the technology.

But if you’re dyslexic, and you use a language model to help you take a really complicated document and distill it down into something that you can more easily understand — bullet points for you, that sort of thing — that’s huge. That’s a game changer for somebody who is struggling to read really dense text in an academic report or something like that.

Same thing with being able to have image descriptions for complicated charts, or maps, and those sorts of things. There’s a lot there that is hugely empowering and really beneficial for a wide variety of people, not just people who have disabilities, but people who want to or who benefit from consuming things in different ways.

I look at captions, for instance. I do have a slight hearing disability. But I started turning captions on when my son was born, and I wanted to be able to watch TV while he was sleeping in my arms. And he’s nine now, and we always watch everything with subtitles on. And he even hates it when there’s not subtitles on now.

And that’s one of the things I don’t like about going to the movie theater now, is I don’t have subtitles. Because frankly, the background noise is always too much, and the audio to the vocals are always too far down.

So I think as we start to broaden our perspectives, we create more opportunities for more people to have better experiences in the world. Same thing with if we go back to the classic example of accessibility of the curb cut.

The curb cuts that were originally created in Berkeley were created by sledgehammers as people were trying to take back their city and try and make it accessible to people in wheelchairs. And they would go out in the middle of the night and smash the curbs in order to create ramps. And now they’re a fixture in most cities.

And it’s not just people in wheelchairs who benefit. It’s the kids on bikes. It’s the people pushing strollers. It’s the delivery people who need to get a ton of packages into a large, high-rise building in downtown. There are so many folks who benefit from that now.

And at the time it was vandalism, right? Like, this was an act of defiance. But now it’s an accommodation that helps so many people. And I think that we can look at technologies like AI and find use cases like that that can be super transformative for everybody.

Because people who are dealing with cognitive issues, cognitive disabilities, they have the same things that some of us may have after a really exhausting day, right? Like, we have cognitive disabilities as well that might be temporary, and we can benefit from the same technology that benefits them every day. And so I think as we look to that kind of expansive opportunity space, we create the real use cases for a lot of these technologies, rather than just these sizzle reels of, oh, look, we have — I can have a witty conversation with this chat agent.

**Jeremy Osborn:** Right.

**Aaron Gustafson:** So?

**Jeremy Osborn:** I guess that kind of leads into my next question. And I’ll just again pause for a second. And folks, anyone who, if you want to start throwing questions in LinkedIn, cool. We’ve got a couple already. But feel free. This is the time just in general, because we’ve got about 10 minutes left.

But to that point, I guess I feel like all three of us were there at kind of the onset of the web. And we saw again it go in several directions, and then take a step back and be like, yeah, that didn’t really work out, did it?

And I’m curious. I do feel like we’re in a little bit of that stage now, where, again, a common — I guess common complaint is being pushed on us in a lot of places where we didn’t ask for it, didn’t expect it, et cetera, et cetera.

And so I guess is that just the nature of adopting a new technology? It just seems like this seems to be so much faster. It’s, like, happening so much more quickly.

**Aaron Gustafson:** I mean, it’s the classic [Gartner Hype Cycle](https://www.gartner.com/en/research/methodologies/gartner-hype-cycle), if folks are familiar with that. You know, the — I forget all the things. I just always remember the trough of disillusionment. But —

**Andrew Miller:** That’s the one that we all remember, isn’t it? We all remember that. Yeah.

**Aaron Gustafson:** Yeah. Yeah, so I think there are some — yeah, there’s a lot of people just throwing things at the wall and seeing what sticks. And there are certainly some compelling examples.

But to me, a lot of the places where I’ve found just real, I don’t know, inspiration behind the work they’re doing is in the disability space and figuring out how these tools can be used to do more. So Chad was asking about the AI for Accessibility grant program, which is another program that I’ve run, where I get to spend Microsoft’s money investing in outside projects and folks who are doing some really interesting things.

There is an organization based out of Radboud University, which is in the Netherlands. And they’ve been working with Masanga Hospital in Sierra Leone, and they are using AI to help them to customize prosthetics for people who have limb loss. They’re specifically focused on below and above elbow and below and above knee amputations.

And what they’re doing is they are using 3D scans of the folks’ stump. And then they bring that model into their software, and they use AI to help them figure out how to create better socket fit with less rubbing. And that is tremendous. And it completely — and then they’re 3D printing the sockets.

And so it is completely revolutionizing the way that prosthetics are being created because the traditional sort of Red Cross model was making a plaster cast, and then doing a — I forget what it’s called. Like a mold of that. And then basically creating it, and it taking like multiple steps. Having to shave it down manually, all of that sort of stuff. It is a very heavily manual process and can be done much more quickly using AI to help them figure that out. Just remarkable stuff.

We’ve worked with Cboard, which it’s the letter C, board, B-O-A-R-D, dot io. And they are one of the AAC software I mentioned earlier. They are an open source AAC software company. And they have been doing tremendous work on their AAC software itself, but they’ve also been doing work on a new product that we actually showed at an Ability Summit, Microsoft’s Ability Summit last week called Fluent Mind AI.

And to the person’s question about aphasia, it could be something really useful for that, where it’s actually — it’s an AAC software, but it’s listening to the conversation that you’re having with people in real time. And then it is listening to that conversation and proposing responses that you might want to give based on what it knows about you.

So it’s really helping you to compose sentences quicker because that’s one of the things that’s very challenging for people who are using AI for — or using AAC software is that it can take 60 to 90 seconds to draft a reply, especially if you’re using eye gaze.

And so this dramatically speeds that up by using speech-to-text, so catching that, and then combining the speech-to-text with a language model to propose potential responses. And then you can choose from those responses or give it a little bit of a hint of a direction you want to go in with your response, and then it will propose a response to you. That’s pretty amazing.

There’s a team at [Global Symbols](https://globalsymbols.com) that are based in the UK, and they are using image generation to create symbol sets for AAC software that remain thematically visually consistent, but are culturally relevant. So being able to — if you were doing a symbol for a police officer, that police officer will probably look different in Britain, versus Indonesia, versus Thailand, versus Japan, China, et cetera. So being able to do that.

They shared a story with us early on about creating symbols, using generative AI to create symbols so that a young man could participate in the Muslim call to prayer which he had not been able to do with his brothers in years. And so all of a sudden, he had the symbols to be able to do that.

And that’s amazing. Like, being able to channel the image generation capabilities of AI to really expand the capacity of AAC software and similar things is really — it creates so much more opportunity for people to live the lives that they want to live and do the things that they need to do.

**Jeremy Osborn:** Yeah. Out of curiosity, this is — so these AI for Accessibility grants, are these things that people — like, if there were people in our audience who might have things that they were curious in doing, this is something that’s like a public submission? Or is it — how does that work?

**Aaron Gustafson:** We have traditionally put out calls, and they’ve usually been thematic. So we’ve had some that have been focused on mental health. We’ve had some that have been focused on generative AI. We’ve had some that have been focused on other areas.

I’m not sure what the future holds for the program right now because my focus is in a couple of different areas. But yeah, that’s traditionally how it’s gone. We’ve put out an RFP. And sometimes we’ll also make strategic investments. If we’re made aware of something and we think it’s really interesting, we might have a couple of conversations with the team and then decide that we want to invest in it outside of a funding round. That has certainly happened. But yeah, there’s some just amazing things.

I know we’re coming up on time. One more I just want to share from the mental health standpoint. Really interesting project.

We worked with an organization in India to create a product called [IWill](https://iwilltherapy.io). And what it is is cognitive behavioral therapy via chatbot. Which to me, when I initially heard the pitch, I was like, oh, that’s kind of scary, right? Like, this is a real, in some cases, a life or death thing for people when you’re talking about folks’ mental health.

But what I came to realize is that there is just a tremendous lack of mental health support for people in India. I don’t remember the exact numbers, but I think it’s like 0.6 mental health professionals per 100,000 people in India. So there’s just — the capacity is just not there to help people.

And so what IWill was doing is they had psychologists on staff who were practicing who were interested in taking — with permission — the transcripts of cognitive behavioral therapy sessions in Hindi end-to-end, and take those, and use those to train a model so that it could do a better job of having conversations with people in Hindi via apps. And so they worked on that, and it’s been extremely successful.

They had a plan to be able to deliver that to people who didn’t have devices themselves because there are a lot of people who don’t have the money for a device. So being able to go to a private room within a community center to be able to engage in CBT is pretty amazing.

So they’re another phenomenal organization doing great work. And they’re continuing to take that even further, doing some voice related stuff for people who are low literacy as well. So there’s some really interesting applications in that space as well.

**Jeremy Osborn:** Cool. We need to figure out how to — I believe that for the folks who have registered for this event, we can go back and put some of these resources. I think, Andrew, we can do this —

**Andrew Miller:** I think we just add it to the chat. I think we can just copy and paste them into the chat.

**Jeremy Osborn:** Exactly. And we can see people — we want to respect their time. People have to take off. So I guess we’ll kind of wrap it up officially.

Thank you so much, Aaron. This was really eye-opening. I think it’s super encouraging to see that people are kind of thinking about the responsible irresponsible uses of AI, and also again, some of the less heralded but meaningful applications of that. So, super encouraging.

Again, for folks who — and I know that one last thing that we’ll do, another link of resources. You’ve written a little bit about this on our favorite web magazine, A List Apart. And there’s a great article that you did there about [opportunities for AI](https://alistapart.com/article/opportunities-for-ai-in-accessibility/), and people should check that out as well.
s
Andrew, any parting words that you have?

**Andrew Miller:** No, just thank you, Aaron, for sharing this with us. It’s so easy to get caught up in the mire of all the negative press and concerns. And you know, nothing is free, right? Nothing is free. But this is absolutely payoff.

So there was a point like, when is AI worth it? When is AI worth the extra cycles at a data center? When is it worth the potential for misuse? And it’s like, these cases are where it’s justified, right? Like, it’s a tool that changes lives in such positive ways. Denying people that would be absurd. We use electricity more frivolously making stupid pictures with AI, right?

**Aaron Gustafson:** 100%.

**Jeremy Osborn:** So I think it’s really important that this work gets showcased because it’s critical. So thank you.

**Aaron Gustafson:** Yeah.

**Jeremy Osborn:** Seconded.

**Aaron Gustafson:** Thank you for having me.

**Jeremy Osborn:** Yeah. So we will end now. Again, thanks, everyone, for joining us. We look forward to do some more of these in the future. And again, Aaron, thank you so much.

**Andrew Miller:** Yeah. Thanks, Aaron.

**Aaron Gustafson:** Yeah. Thank you for the conversation. I really enjoyed it.

**Jeremy Osborn:** All right. And — [END LIVESTREAM]
