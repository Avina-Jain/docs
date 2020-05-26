The Clarifai Knowledge graph enables you to map the custom concepts in your model to a common set of concepts. The knowledge graph makes it possible to link data across multiple custom and pre-built models in a meaningful way.

The knowledge graph is organized by the relationship between concepts as either hypernyms, hyponyms, and synonyms.

*Hypernym* is a word with a broader meaning that encapsulates words with more specific meaning falling under it. Cutlery will be a hypernym to knives.
*Hyponym* is a word with more specific meaning and is the opposite of hypernym. Knives would be a hyponym to cutlery.
*Synonym* is a word with similar meaning to another word.

You can create these mappings in your application with a few easy steps.  

1. Consider the following application that has four concepts: beverages, smoothie, breakfast, and french_toast. You can use the Knowledge Graph to create hierarchical relationships between the concepts.

![](../../images/kg1.png)

2. You can link concepts as hierarchical by going to the details of either of the concepts. In the shown application, french_toast falls under breakfast. You can link them by accessing the View Details section of either concept.

![](../../images/kg2.png)

3. Once, in the details dashboard, you can link breakfast as a hypernym to french_toast under the Input Relations menu.

![](../../images/kg3.png)

4. Once you list breakfast as a hypernym to french_toast, it will set french_toast as a hyponym to breakfast automatically.

![](../../images/kg4.png)

5. This process can be used to create similar relationships between beverages and smoothie. Beverages will be listed as a hypernym to smoothie.

![](../../images/kg5.png)

6. By doing this, smoothie will be listed as a hyponym to beverages automatically.

![](../../images/kg6.png)