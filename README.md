# why this repository?

I searched for ontology of Japanese language. I found that
# https://github.com/wikipedia-ontology is wrongly named as "Japanese Wikipedia Ontology
", though the phrase "Learning a Large Scale of Ontology from Japanese Wikipedia" is very right.
# "Ontology-Based Natural Language Parser for E-Marketplaces"(DOI: 10.1007/11504894_39) utilizes ontology of commodities, rather than that of the "natural language".
# WordNet or Japanese WordNet are not of the English language or Japanese language.

Hence, this repository is dedicate to ontology of Japanese language(Japanese ontology).

The should-be meaning of "Japanese Ontology"

It should be another perspective of Japanese grammar(https://en.wikipedia.org/wiki/Japanese_grammar) or dictionary, but in a formal way.
we can say it is the rules of the Japanese language.
So the database should contain entities such as phonetic stuff, character(word), phrase, pattern, and the meaning of each entity.
The pattern describes the ontological relation between other entities, though I have not choose how to represent each item(entity or relation).

For examples, 
#0 の: of possion.
#1 pattern AのB: describes belonging relation: B belongs to A, A possesses B.
#2 patern Aの: の terminates a setence, and the meaning of it in such cases.
#3 Aの上で: means on the top of A
#4 pattern A上: in the field of A
#5 A上のB: means B is a property or (properties) of the topic, and B is in the field A
#6 植物学: botany, plant biology, of pattern #10. We don't get into the meaning of it since that belongs to the ontology of biology. Here, we focus on the meta-ontology of biology, i.e. the language used to describe the study of biology. And in this case, the meta-ontology of biology is the ontology of Japanese language.
#7 特徴: characteristics
#8 学: the root of verb 学ぶ
#9 A学: science of subject A.
#10 植物: plants

Once this project is substantial, then for the above mentioned 2 papers.
# Japanese sentences(paragraphs) on Japanese wikipedia would the great material for marking with this ontology database.
Then for example the phrase "植物学上の特徴"(from https://ja.wikipedia.org/wiki/%E3%83%AA%E3%83%B3%E3%82%B4) would be marked with ontology items:
some of its words(if not every word) are associated with their corresponding ontology items.
植物 is not needed to be associated with anything, though we can associated it to #10.
学 to be associated with not#8
植物学 to be associated with #6 and #9 with A="植物"
上  to be associated with #4, and A="植物学"
の  to be associated with #0 and #1, and A="林檎",B="特徴"
特徴 to be associated with #7
and the whole phrase to be associated with #5 with A="植物学", B="特徴", topic="林檎"

With this huge set of marking, the characteristics of the Japanese language would be fully covered. And with the knowledge of this coverage, then any other Japanese setence not in this set could be well understood.

# with the ontology of commodities and the meta-ontology of commodities(i.e. the ontology of the English language for the case of DOI: 10.1007/11504894_39).
