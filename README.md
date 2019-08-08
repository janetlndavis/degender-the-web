# Degender the Web - a Chrome extension
What if English had no gender pronouns? 
Inspired by [Farhad Manjoo](https://www.nytimes.com/by/farhad-manjoo)'s essay 
[It's Time for 'They'](https://www.nytimes.com/2019/07/10/opinion/pronoun-they-gender.html), 
_Degender the Web_ is a Chrome web browser extension that replaces gendered personal pronouns on most Web pages with "they/them/their".

_Degender the Web_ is both a thought experiment and a behavior change support system.
When you install it, you will see how the singular "they" can function as a universal pronoun.
As you use it over time, you should become more comfortable with the singular "they" in reading, writing, and speech. 

Gender-neutral pronouns added by this extension will appear with a faint dashed underline. 
Mouse over to see the original, gendered pronoun. 
Text that you write or edit, e.g., in a form or on Google Docs, will not be modified.
The original text can be restored with the click of a button.

This extension does not collect personally identifiable information. See the [privacy policy](PRIVACY.md) for more information.

Note that this extension runs the risk of misgendering persons, both trans and cis, 
who have stated their use of "he/him" or "she/her" prounouns. 
Though it can never be eliminated entirely, several design features will aim to mitigate that risk. In particular, the extension does ot alter personal pronouns on pages that
* include a personal pronoun specifier, [such as "he/him" or "she/her"](data/personal-pronoun-specs.json);
* include the word "gender" in the page text, suggesting that the page may address gender as a topic.

[A few domains](data/excluded-domains.json) are excluded due to technical incompatibilities.

Other potential mitigation features are currently documented as [issues](https://github.com/ProfJanetDavis/degender-the-web/issues) 
and will be documented here when they are implemented. 
See also the invitation to contribute below.


## Learning more

To learn more, read some of the following contributed links:
* [Understanding Non-Binary People: How to be Respectful and Supportive](https://transequality.org/issues/resources/understanding-non-binary-people-how-to-be-respectful-and-supportive) - A very concise guide provided by the National Center for Transgender Equality.
* [What is the Singular They, and Why Should I Use it?](https://www.grammarly.com/blog/use-the-singular-they/) - An accessible introduction  from Grammarly.
* [Singular 'They'](https://www.merriam-webster.com/words-at-play/singular-nonbinary-they) - On Merriam-Webster's list of "words we're watching."
* [Even A Grammar Geezer Like Me Can Get Used To Gender Neutral Pronouns](https://www.npr.org/2019/08/06/744121321/even-a-grammar-geezer-like-me-can-get-used-to-gender-neutral-pronouns) - How? By practicing!
* [Why We Should All Use They/Them Pronouns](https://blogs.scientificamerican.com/voices/why-we-should-all-use-they-them-pronouns/) - An argument for the stronger claim that we should do away with gendered pronouns altogether.
* [Actually, We Should _Not_ All Use They/Them Pronouns](https://blogs.scientificamerican.com/voices/actually-we-should-not-all-use-they-them-pronouns/) - A response to the above, by "a mix of queer, nonwhite, non-American, bicultural, trans people."
* [Pronoun Privilege](https://www.nytimes.com/2016/09/26/opinion/pronoun-privilege.html) - An essay on pronoun use in the classroom.
* [They Is My Pronoun](http://www.theyismypronoun.com/) - "TIMP focuses on actually using singular they in real life, and on enabling the choice to use gender-neutral pronouns for yourself or for others."


For a review of technology designed to influence language use, see this prior work:

>Emma Twersky and Janet Davis. 
>["Don't say that!" An analysis of persuasive systems in the wild.](http://cs.whitman.edu/~davisj/pubs/Persuasive2017_031_final.pdf)
>In de Vries, P.W., Oinas-Kukkonen, H., Siemons, L., Beerlage-de Jong, N., van Gemert-Pijnen, L. (Eds.), _Proceedings of the 12th International Conference on Persuasive Technology (PERSUASIVE 2017)_, Amsterdam, The Netherlands, April 4-6, 2017. Springer, LNCS 10171, pages 215-226.

## Contributing

Contributions from the community are welcome. Please [create a GitHub issue](https://github.com/ProfJanetDavis/degender-the-web/issues/new/choose):
* if you identify situations in which the singular pronoun 'they' is conjugated incorrectly;
* if you identify a site on which this extension should not run;
* if you encounter other unexpected behavior (bugs) while using this extension;
* if you have suggestions for additional features.

Developers are welcome to submit a pull request. See [information for developers](DEVELOPMENT.md).

## Acknowledgments

Thanks to Kristen Peter Mork for sharing Farhad Manjoo's essay. Thanks also to Sarah Peterson, Ellie Poley, and Syd Ryan for contributing to the links listed above. Thanks to all for conversations about this project.

Thanks to Andy Exley and Robert Grimm for technical advice. 
Thanks to Spencer Kelly for maintaining the Compromise JavaScript NLP library.

This work is supported by [Whitman College](https://www.whitman.edu/) and the Microsoft Chair in Computer Science. Thanks to Gillian Frew for assisting with media strategy. 

This Chrome extension is inspired by earlier text replacement extensions such as 
[HonestChrome](http://untitledscience.github.io/HonestChrome/).

Additional acknowledgments will be added as permissions are obtained.
