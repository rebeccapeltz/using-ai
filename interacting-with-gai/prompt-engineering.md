# Prompt Engineering

Prompt Engineering is a process that optimizes inputs to GAI to maximize the output. Prompt Engineering requires a good understanding of what you want to achieve in conversion with the model.  It would be best to understand what the model you're working with can provide you.  You wouldn't ask Gemini to create an image because it doesn't work with that media.  &#x20;

Without this process, GAI will respond with questions to help determine your needs.   For example, if you submit the word **cupcake** to ChatGPT, it will output this:

> Are you looking for a recipe, information about different types of cupcakes, or something else related to cupcakes? Let me know how I can help!

In this example, GAI uses prompt engineering to make your input more specific. &#x20;

### Set Goals for your interaction

Knowing these goals, you can integrate them into the text you use in your input.

1. What type of media do you want to produce?
2. If you are planning on sharing the output, who is your audience?
3. What style do you want the output to be presented in? Should it be casual or formal?

#### Add Details and Context

GAI is  "listening" to words to help it "understand" and craft content that matches the words in the prompt.   Changing the cupcake prompt to a more detailed question will give you the answer you want.  Create a prompt for **cupcakes** to find a recipe for a specific type of cupcake you want to serve in a particular location.

Here is the prompt.

> Create a recipe for a cupcake that I can serve to children at their school. It should contain healthy ingredients like raisons, coconuts, and walnuts.  The frosting cannot contain milk because some of the children may be alergic to it.  If any of the ingredients could cause alergies, alert me.

Here is the response from ChatGPT when I use a detailed prompt with context.

> OpenAI. (2024). _ChatGPT_ \[Large language model]. https://chatgpt.com/c/a074cd91-8940-40e7-93e9-005bc6010ddd
>
> #### Healthy Raisin, Coconut, and Walnut Cupcakes
>
> **Ingredients:**
>
> **Cupcakes:**
>
> * 1 cup whole wheat flour
> * 1/2 cup rolled oats
> * 1/2 teaspoon baking soda
> * 1 teaspoon baking powder
> * 1/4 teaspoon salt
> * 1/2 cup unsweetened applesauce
> * 1/4 cup coconut oil (melted)
> * 1/4 cup honey or maple syrup
> * 2 large eggs
> * 1 teaspoon vanilla extract
> * 1/2 cup raisins
> * 1/2 cup shredded coconut (unsweetened)
> * 1/2 cup chopped walnuts
>
> **Frosting:**
>
> * 1/2 cup coconut cream (chilled, thick part only)
> * 2 tablespoons honey or maple syrup
> * 1 teaspoon vanilla extract
> * Optional: 1-2 tablespoons cocoa powder for a chocolate version
>
> **Instructions:**
>
> 1. **Preheat and Prepare:** Preheat your oven to 350°F (175°C). Line a cupcake pan with paper liners or lightly grease it.
> 2. **Mix Dry Ingredients:** In a large bowl, combine whole wheat flour, rolled oats, baking soda, baking powder, and salt.
> 3. **Mix Wet Ingredients:** In another bowl, whisk together the applesauce, melted coconut oil, honey or maple syrup, eggs, and vanilla extract.
> 4. **Combine:** Gradually mix the wet ingredients into the dry ingredients until just combined. Fold in the raisins, shredded coconut, and chopped walnuts.
> 5. **Bake:** Divide the batter evenly among the cupcake liners. Bake for 18-22 minutes, or until a toothpick inserted into the center comes out clean.
> 6. **Cool:** Let the cupcakes cool in the pan for 5 minutes before transferring them to a wire rack to cool completely.
> 7. **Make the Frosting:** While the cupcakes are cooling, prepare the frosting. In a chilled bowl, whisk together the coconut cream, honey or maple syrup, and vanilla extract until smooth and fluffy. If using cocoa powder, fold it in now.
> 8. **Frost:** Once the cupcakes are completely cool, frost them with the coconut cream frosting.
>
> **Allergy Notes:**
>
> * **Walnuts** are a tree nut and can cause allergic reactions in children with nut allergies. You may want to substitute them with sunflower seeds or omit them entirely.
> * **Coconut** is generally considered safe, but it's technically a tree nut, so check with the school or parents if this could be an issue.
>
> These cupcakes are a healthier option with whole grains, natural sweeteners, and no dairy, making them suitable for children with milk allergies.

### Analysis of the Output and Iteration

Once you get this detailed response, analyze it to see if it fulfills your goals.  In this situation, you see that some ingredients trigger allergies, so you may want to rerun your prompt and include instructions not to use any allergy-producing ingredients. &#x20;

The word iteration means **repetition of a process**.   As you generate content and find problems, you must repeat the process with adjustments and more information to zero in on content that satisfies your goals.

### Different Approaches for Different Outcomes

#### Role Playing

When you craft your input, you can cast the AI in a role such as **expert**, **poet**, **storyteller**, **technical advisor**, or **instructor**.   These are just examples.  You can specify whatever role suits your prompt. &#x20;

#### Brainstorming

GAI is excellent for brainstorming ideas.  When you're trying to develop ideas for a project you're working on, rather than presenting a detailed prompt, you can create prompts similar to questions you might ask in a brainstorming session.

#### Example

Consider a situation in which you work in marketing for a cybersecurity company. The company has created a product that will help elderly people avoid being hacked by phishing (clicking on links that trigger malware).&#x20;

Here's the prompt given to ChatGPT:

> I'm developing a new product that helps elderly people to thward phishing attempts. I need help creating a product description.

Here's the output where ChatGPT provides me with everything I need to market the product.

> #### Product Description for Anti-Phishing Tool for Elderly Users
>
> **Product Name:** SecureGuard
>
> **Tagline:** Empowering Seniors to Stay Safe Online
>
> **Description:**
>
> SecureGuard is an innovative tool designed to protect elderly users from online threats, specifically phishing attacks. With the increasing complexity of cyber scams, seniors are often targeted due to their trusting nature and lack of familiarity with evolving digital dangers. SecureGuard is here to change that, offering an easy-to-use solution that empowers older adults to navigate the internet confidently and safely.
>
> **Key Features:**
>
> 1. **Real-Time Phishing Detection:** SecureGuard uses advanced AI algorithms to analyze emails, websites, and messages in real-time, detecting suspicious content and alerting users before they can fall victim to scams.
> 2. **Simple, User-Friendly Interface:** Designed with seniors in mind, SecureGuard features a clean, intuitive interface with large icons and clear instructions, ensuring that even those with limited technical skills can use it with ease.
> 3. **Guided Learning:** The built-in educational tool provides step-by-step guidance on identifying common phishing tactics. Through interactive tutorials, users can learn how to spot and avoid potential threats.
> 4. **Customizable Alerts:** SecureGuard allows users to customize alert settings according to their comfort level, providing them with a sense of control while ensuring their safety.
> 5. **Automatic Updates:** The software continuously updates itself with the latest threat information, ensuring that users are protected against new and emerging phishing tactics.
> 6. **24/7 Support:** SecureGuard offers around-the-clock customer support, with a dedicated team available to assist users with any concerns or questions.
>
> **Benefits:**
>
> * **Peace of Mind:** SecureGuard provides elderly users and their families with confidence, knowing they are protected from online fraud.
> * **Independence:** Seniors can maintain their independence online without constantly needing assistance from others.
> * **Safety and Security:** With SecureGuard, the risk of falling victim to phishing attempts is significantly reduced.
>
> **Target Audience:** SecureGuard is ideal for elderly users who regularly use the internet for communication, shopping, banking, or any other online activity. It’s also a perfect gift for concerned family members who want to ensure their loved ones are safe online.
>
> **Conclusion:** SecureGuard is more than just a tool—it's a protective companion in the digital world, helping elderly users stay safe from phishing scams and empowering them to enjoy the benefits of the internet without fear.

### Summary from Google Gemini

When you're creating prompts for GAI, keep these directives from Gemini in mind:

* **Be specific:** Provide clear instructions and avoid ambiguity
* **Provide context:** Give the model the necessary background information
* **Use examples:** Show the model your desired output formats
* **Incorporate keywords:** Guide the model towards relevant information
* **Experiment with different phrasing:** Try various approaches
