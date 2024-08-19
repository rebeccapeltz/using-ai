# Generative AI using LLM Models

Chances are you've used a search engine like Google.  You're interested in information about a specific topic, so you type that topic name into the Google search input and wait for Google to return a list of websites that might satisfy your interest.  Although the technology behind this is very different, the user experience for interacting with GAI may feel similar.  You'll provide a request prompt in the form of a question or a command, and after some processing, the GAI model will return content that fulfills your request.  Let's look at how the technology behind this program works.

### Large Language Models and Generative AI

&#x20;Multiple audiences want to understand how LLMs are built and used to create GAI. Many are interested in implementing the code to write an LLM. In this course, we are ultimately interested in interacting with Generative AI, not how to code it.  However, the more we understand how GAI is created, the better we'll appreciate what makes a good prompt.

Let's let Google Gemini describe how LLM's are built and used in GAI.  We'll ask it this question:

> How would you describe creating generative AI using LLms for non-programmers?

Now, let's see how Gemini responded:

> ### Creating Generative AI with LLMs: A Simple Explanation
>
> **Imagine teaching a child to write stories.** You start by reading them countless books. Over time, they learn about different characters, plots, and writing styles. Eventually, they can create their own stories based on what they've learned.
>
> **That's essentially what we do with Large Language Models (LLMs) to create Generative AI.**
>
> * **LLMs are like super-smart children:** They're fed massive amounts of text data - books, articles, code, and more.
> * **Learning to write:** As they process this information, they learn patterns, grammar, and how to structure different kinds of text.
> * **Creating something new:** Once trained, we can give the LLM a prompt (like "Write a story about a robot who wants to be a chef") and it uses its knowledge to generate new text.
>
> **So, creating Generative AI with LLMs is like training a super-intelligent writing assistant.** It's about feeding it lots of information, letting it learn, and then asking it to create something original based on what it's learned.



Gemini starts with a metaphor, reminding us how we teach children to write stories: We read them "countless books." After they've read a lot of books, they start to see patterns, which they can then use to write their own books.  Then we find out that LLMs are like "super-smart" children who can read lots of "books" . This means they read lot of data which can include books, articles, and code.  They can then process this information in a way that allows them to share summaries using human language.&#x20;

### Neural Networks

Even though we won't be coding an LLM, we can look at the data flow through a neural network.  LLMs use neural networks to process data
