---
description: Create prompts to help solve problems encountered at work.
---

# Work

<figure><img src="../.gitbook/assets/pexels-cottonbro-6804076.jpg" alt=""><figcaption><p>Using AI to Solve Problems at Work</p></figcaption></figure>

The [bottom of this page](work.md#list-of-common-problems-encountered-at-work) lists common problems encountered at work. The topics range from writing a blog post to generating code and analyzing data.  Choose an item not covered here and use one of the LLMs (Gemini, ChatGPT, or Claude.ai) to find a solution.

The problems addressed here are:

* [Product to Market](work.md#problem-1-product-to-market)
* [Research with Formatted Output](work.md#problem-2-research-with-formatted-output)
* [Data in Tabular Format](work.md#problem-3-data-in-a-tabular-format)

### Problem 1:  Product to Market

Getting a product to market involves creating communication understandable by both the customer and the employees selling the product.  For this product, there are three phases:&#x20;

* Define the product.
* Translate the definition to any language that a potential customer or employee uses.
* Create a Sales Script.

#### Problem Definition

If you work in sales or marketing, having a sales script to reference when calling a potential customer is helpful. The script can include the product name, features, and pricing. This example creates a product description, a product description translation into Spanish, and a sales script that explains the product's features and pricing.

This problem is solved using three steps, each using a different model. One way to experiment with the differences in models is to use different models with the same prompt and then compare the output.

#### Step 1: Create a Product Description

The prompt describes that product and its pricing. ChatGPT then asked if I wanted help developing this product, so I asked it to create a document that describes it that I could share with investors.

#### Model: ChatGPT



{% tabs %}
{% tab title="Prompt" %}
OpenAI. (2024). _ChatGPT_ \[Large language model]. https://chatgpt.com/c/382cb0b7-20c6-40ef-ab2e-963850f66ac6

I'm working on a product named "No Phish Tonight" that helps prevent phishing attacks. It will be a browser extension. You can run it on any web page, but running it on a web page with an open email will be especially helpful. The extension will locate phishing links and report them to a central service for investigation. Each user will have access to a dashboard to learn more about phishing attempts perpetrated on them. There will be a free play that allows for 1000 free searches. There will be two additional plans: up to 10,000 searches for $5/month and unlimited searching for $15/month.
{% endtab %}

{% tab title="ChatGPT Response" %}
That sounds like a valuable tool for enhancing online security! With the "No Phish Tonight" browser extension, users will have a powerful resource to protect themselves from phishing attacks, especially when browsing emails or potentially malicious web pages. The tiered pricing plan offers flexibility for different user needs, making it accessible to casual and heavy users.

If you need help with further development, marketing strategies, or any other aspect of launching your product, feel free to ask!
{% endtab %}

{% tab title="Prompt #2" %}
Please create a document that describes this product and lays out the information that I described. I can use this document to communicate how to develop this product and make it understandable to investors.
{% endtab %}

{% tab title="ChatGPT Response" %}
No Phish Tonight - Product Overview

No Phish Tonight is an innovative browser extension designed to protect users from phishing attacks. As phishing continues to be a prevalent threat in the digital landscape, this tool provides users with a robust solution to detect and report malicious links, particularly on web pages with open emails.

## Product Features

• \*\*Browser Extension\*\*: No Phish Tonight operates as a browser extension that can be run on any web page. It is especially effective when used on web pages containing open emails, where phishing attempts are most likely to occur.

• \*\*Phishing Link Detection\*\*: The extension scans web pages for phishing links. If any are found, they are immediately flagged and reported to a central service for further investigation.

• \*\*User Dashboard\*\*: Each user has access to a personalized dashboard. This dashboard provides detailed insights into the phishing attempts that have been detected and reported. Users can view summaries, statistics, and trends related to phishing attacks.

## Pricing Plans

• \*\*Free Plan\*\*: The free plan allows users to conduct up to 1,000 phishing link searches per month. This option is ideal for casual users who want basic protection at no cost.

• \*\*$5/month Plan\*\*: This plan provides users with up to 10,000 searches per month, catering to more active users who need enhanced protection and higher usage limits.

• \*\*$15/month Plan\*\*: For users requiring unlimited searches, this plan offers comprehensive protection with no restrictions on the number of searches. It is best suited for heavy users or businesses looking for maximum security.

## Conclusion

No Phish Tonight is poised to become an essential tool for anyone concerned about online security. With its intuitive interface, powerful detection capabilities, and flexible pricing plans, it offers a solution that can scale to meet the needs of both individual users and organizations. Whether it's for personal use or enterprise-level protection, No Phish Tonight provides the peace of mind that comes with knowing your digital environment is secure.
{% endtab %}
{% endtabs %}

#### Step 2:   Language Translation

We work with people from many different countries around the world. We often need to communicate with someone who speaks a different language.  Whether in person, on a Zoom call, talking face to face, traveling to a country that speaks a different language,  or creating product information for customers in another country, we may need to translate.  There are many translation options, and GenAI is only one of them.

In this dialog with Gemini, I ask them to translate my **No Phish Tonight** product description from English to Spanish.  The prompt asks Gemini to translate the text shared into Spanish. It takes less than a second to get the translation.

#### Model: Gemini

{% tabs %}
{% tab title="Prompt" %}
Can you translate this text into Spanish:  \<product description produced in Problem 1>


{% endtab %}

{% tab title="Gemini Response" %}
### No Phish Tonight - Resumen del Producto

**No Phish Tonight** es una innovadora extensión para navegadores diseñada para proteger a los usuarios de ataques de phishing. A medida que el phishing continúa siendo una amenaza frecuente en el panorama digital, esta herramienta brinda a los usuarios una solución sólida para detectar y reportar enlaces maliciosos, especialmente en páginas web con correos electrónicos abiertos.

**Características del Producto**

* **Extensión para Navegador**: No Phish Tonight funciona como una extensión para navegadores que se puede ejecutar en cualquier página web. Es especialmente efectiva cuando se usa en páginas web que contienen correos electrónicos abiertos, donde es más probable que ocurran intentos de phishing.
* **Detección de Enlaces de Phishing**: La extensión escanea las páginas web en busca de enlaces de phishing. Si se encuentran alguno, se marcan inmediatamente y se reportan a un servicio central para su investigación.
* **Panel de Control del Usuario**: Cada usuario tiene acceso a un panel de control personalizado. Este panel proporciona información detallada sobre los intentos de phishing que se han detectado y reportado. Los usuarios pueden ver resúmenes, estadísticas y tendencias relacionadas con los ataques de phishing.

**Planes de Precios**

* **Plan Gratuito**: El plan gratuito permite a los usuarios realizar hasta 1,000 búsquedas de enlaces de phishing por mes. Esta opción es ideal para usuarios casuales que desean protección básica sin costo.
* **Plan de $5/mes**: Este plan proporciona a los usuarios hasta 10,000 búsquedas por mes, atendiendo a usuarios más activos que necesitan protección mejorada y límites de uso más altos.
* **Plan de $15/mes**: Para usuarios que requieren búsquedas ilimitadas, este plan ofrece protección integral sin restricciones en el número de búsquedas. Es más adecuado para usuarios intensivos o empresas que buscan la máxima seguridad.

**Conclusión**

No Phish Tonight está preparado para convertirse en una herramienta esencial para cualquier persona preocupada por la seguridad en línea. Con su interfaz intuitiva, poderosas capacidades de detección y planes de precios flexibles, ofrece una solución que puede adaptarse a las necesidades de usuarios individuales y organizaciones. Ya sea para uso personal o protección a nivel empresarial, No Phish Tonight brinda la tranquilidad que proviene de saber que su entorno digital es seguro.
{% endtab %}
{% endtabs %}

#### Step 3:  Sales Script

In this dialog, I'm asking Claude.ai to create a Sales Script from the product description I made in Step 1.  So the output of Problem 1 is pasted into this prompt where it says _\<product description produced in Problem 1>_.

At the end of Claude.ai's response, it asks, "Would you like me to modify or expand on any part of this script?"  I responded that it was good as it was now, but I could return if I found more that I wanted to add to it.

#### Model: Claude.ai

{% tabs %}
{% tab title="Prompt" %}
I've created a description of a cybersecurity product I am working on. Can you create a sales script that could be used to describe this product and its features and pricing to a potential customer or investor? Here is the contents of the product description: \<product description produced in Problem 1>
{% endtab %}

{% tab title="Claude.ai Response" %}
Here's a sales script for your No Phish Tonight product:

"Hello, I'm \[Your Name] from No Phish Tonight. We've developed a cutting-edge browser extension that's revolutionizing online security. Let me ask you this: How confident are you that you can spot every phishing attempt in your emails?

In today's digital world, phishing attacks are more sophisticated than ever. That's where No Phish Tonight comes in. Our browser extension is your personal cybersecurity guard, working tirelessly to keep you safe online.

Here's how it works:

1. Install our extension on your browser.
2. As you browse, especially when viewing emails, No Phish Tonight scans for potential phishing links.
3. If a threat is detected, it's immediately flagged and reported to our central service.
4. You can track all this activity on your personalized dashboard, giving you insights into the threats you've avoided.

We offer flexible pricing to suit different needs:

* Our Free Plan gives you 1,000 searches per month at no cost.
* For just $5 a month, you get 10,000 searches, perfect for more active users.
* And for unlimited protection, our $15 monthly plan has you covered with no search limits.

Imagine browsing with complete peace of mind, knowing you're protected from phishing attempts. That's what No Phish Tonight offers.

Would you like to start with our Free Plan to see how it works for you? Or, given your online activity, perhaps one of our paid plans would be a better fit?

What questions can I answer for you about No Phish Tonight?"

Would you like me to modify or expand on any part of this script?
{% endtab %}
{% endtabs %}



***

### Problem 2:  Research with Formatted Output

Many professions require research to create a shared report, write a paper, or provide information for a customer. The report format is essential, and GenAI can generateOpenAI. (2024). _ChatGPT_ \[Large language model]. https://chatgpt.com/c/5b8eb438-9a68-4045-a1ba-59cfe1b9e0f6 a text report formatted according to the prompt's specifications.

#### Problem Definition

A higher education institution studies how to integrate or block the use of AI in courses.  Instructors have been tasked with creating reports that address the pros and cons of integrating AI.  A report format is required for submittal of the report.  The format must summarize an aspect of the problem, provide a bullet point list, and end with a paragraph giving direction.

#### Model: ChatGPT

{% tabs %}
{% tab title="Prompt" %}
Create a report that summarizes the role that AI can play in education. Start with a paragraph that discusses the sentiments expressed by educators and what some of the positive effects of AI can be in education. List a set of bullet points summarizing AI's benefits in education. Add a final paragraph providing direction for using AI in education.
{% endtab %}

{% tab title="ChatGPT Response" %}
OpenAI. (2024). _ChatGPT_ \[Large language model]. https://chatgpt.com/c/5b8eb438-9a68-4045-a1ba-59cfe1b9e0f6

#### The Role of AI in Education

Educators have expressed a mix of sentiments regarding the integration of AI into education, ranging from enthusiasm to concern. On the positive side, many educators recognize the potential of AI to enhance learning experiences, streamline administrative tasks, and provide personalized support to students. AI's ability to analyze vast amounts of data allows for tailored learning paths that adapt to the needs of individual students, potentially leading to better engagement and outcomes. However, there are also concerns about the implications of AI, such as the risk of over-reliance on technology and the potential erosion of human elements in education. Nonetheless, when used thoughtfully, AI can be a powerful tool to complement and enhance traditional educational practices.

#### Benefits of AI in Education

* **Personalized Learning:** AI can adapt educational content to meet the needs of individual students, helping them learn at their own pace and according to their unique learning styles.
* **Efficient Administrative Tasks:** AI can automate routine tasks such as grading, scheduling, and student record management, freeing up educators to focus on teaching and mentoring.
* **Enhanced Learning Materials:** AI can help create interactive and engaging educational content, such as virtual labs, simulations, and augmented reality experiences, that enhance students' understanding of complex subjects.
* **Early Identification of Learning Gaps:** By analyzing student performance data, AI can identify areas where students may be struggling and suggest targeted interventions before problems become more significant.
* **24/7 Support:** AI-driven chatbots and virtual assistants can provide students with instant help and guidance, making educational support accessible at any time.
* **Data-Driven Insights:** AI can generate insights from educational data, helping educators understand trends, predict outcomes, and make informed decisions to improve teaching strategies and student success.

#### Direction for Using AI in Education

To effectively integrate AI into education, it is crucial to strike a balance between technological innovation and the preservation of human elements in teaching. Educators and institutions should focus on using AI as a supportive tool that enhances, rather than replaces, the role of teachers. This involves ongoing training for educators to ensure they are equipped to use AI tools effectively and responsibly. Additionally, clear ethical guidelines and policies should be established to address concerns related to privacy, bias, and equity in AI applications. By carefully managing the integration of AI, educational institutions can leverage its benefits while maintaining a student-centered approach that fosters creativity, critical thinking, and personal growth.
{% endtab %}
{% endtabs %}

***

### Problem 3: Data in a Tabular Format

Formatting data in a table helps analyze a problem.  Gemini is useful for creating tabular data output.  Responses that include data provide answers that often lead to more questions.  The nature of prompting in AI is an excellent setup for inviting the user to keep asking for more data to help understand a situation.

#### Problem Definition

The world has been experiencing a gradual earth warming since pre-industrial times, a phenomenon often called Climate Change. The warming of the earth manifests itself in many different ways. Some have questions about whether Climate Change is real. An excellent place to start analyzing this is to ask for data in a tabular format. &#x20;

This format has two prompts because the data returned by the first prompt triggers a question fed into the second prompt.  The first prompt showed triple-digit temperatures for five states in 2024.  The second prompt ask for the highest temperatures for each of those states in 1960 to see if temperatures had risen over 84 years.

#### Model: Gemini

{% tabs %}
{% tab title="Prompt" %}
Create a table listing states in the United States that experienced the highest temperatures in 2024. The table should contain two columns: the first column should contain the state's name, and the second should contain the temperature in degrees Fahrenheit.&#x20;
{% endtab %}

{% tab title="Gemini Response" %}


| State      | Highest Temperature (°F) |
| ---------- | ------------------------ |
| California | 120                      |
| Arizona    | 120                      |
| Nevada     | 118                      |
| Texas      | 117                      |
| New Mexico | 116                      |
{% endtab %}

{% tab title="Prompt #2" %}
Could you create a table listing states in the United States that experienced the highest temperatures in 2024 and their highest temperature in 1960? The table should contain three columns: the first column should contain the state's name, the second should contain the temperature in 1960, and the third column should contain the temperature in 2024. All temperatures should be reported in degrees Fahrenheit.&#x20;
{% endtab %}

{% tab title="Gemini Response #2" %}


<table><thead><tr><th width="190">State</th><th>Highest Temperature (1960)</th><th>Highest Temperature (2024)</th></tr></thead><tbody><tr><td>California</td><td>116</td><td>120</td></tr><tr><td>Arizona</td><td>115</td><td>122</td></tr><tr><td>Nevada</td><td>112</td><td>118</td></tr><tr><td>Texas</td><td>110</td><td>117</td></tr><tr><td>New Mexico</td><td>108</td><td>116</td></tr></tbody></table>
{% endtab %}
{% endtabs %}



***

### List of Common Problems Encountered at Work

**Product Definition**

**Blog Post**

**Social Media Content**

**Ad Copy**

**Copy Writing**

* Marketing materials
* Product descriptions
* Sales Scripts

**Proof Reading/Editing**

**Summarization**

**Fact-Checking**

**Data Analysis**

**Report Generation**

**Brainstorming**

**Decision Support**

**Troubleshooting**

**Language Translation**

**Language Learning**

**Style and Citation Guides**

**Software Engineering and Code**

* Generation
* Explanation
* Debugging
* Architecture

**Storytelling**

* Scriptwriting
* Poetry generation

**Medical**

* Diagnosis from symptoms
* Pharmaceutical information
* Where to find treatment for specific conditions

**Legal**

* Information needed to create a will
* Referrals
* Document drafting

**Finance**

* Learn financial concepts
* Research and analysis

