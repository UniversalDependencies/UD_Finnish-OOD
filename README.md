# Summary

Finnish-OOD is an external out-of-domain test set for Finnish-TDT annotated natively into UD scheme.


# Introduction

The treebank contains texts from anonymized nursing narratives (hospital patient records), discussion forums, tweets, general web crawls and poetry collected from the Internet. Text sources are marked as sentence identifier prefixes (`# sent_id = identifier`), cl = nursing narratives, thread = discussion forums, tweet = tweets, web = web crawl, and poem = poetry. The document structure can also been resolved from the sentence identifiers.

# License / Copyright

The annotations of the UD_Finnish-OOD are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see http://creativecommons.org/licenses/by-sa/4.0/.

The underlying texts come from various sources collected from the Internet. These may hold different copyright owners.


# Acknowledgments

Annotation: Jenna Kanerva

Text sources collected by TurkuNLP research group, especially Jenna Kanerva, Filip Ginter, Veronika Laippala and Juhani Luotolahti.

The poetry section is extracted from the Finnish Corpus of Online Registers (FinCORE, [link](https://github.com/TurkuNLP/FinCORE)), and the web crawl section is extracted from the Finnish Internet Parsebank ([link](https://turkunlp.org/finnish_nlp.html#parsebank)).

## References

```
@inproceedings{kanerva-2022-ood,
    title = "Out-of-Domain Evaluation of Finnish Dependency Parsing",
    author = {Kanerva, Jenna and Ginter, Filip},
    booktitle = "Proceedings of the 13th International Conference on Language Resources and Evaluation (LREC'22)",
    year = "2022",
    pages = "1114‑-1124",
    url = "http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.120.pdf"
}
```


# Changelog

* 2020-10-30 v2.17
  * Correct three instances of double object marking (rueter)
  * Add candidate=nsubj:exist attribute-value pair to misc for inspection and release in v2.18 (rueter)
* 2020-11-15 v2.7
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.7
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: medical web social poetry
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Kanerva, Jenna
Contributing: elsewhere
Contact: jmnybl@utu.fi
===============================================================================
</pre>
