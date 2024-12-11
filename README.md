# deal_with_massw



12.5
Using Massw as an extension for litsearch.
Ground truth

model
Inline-citation-broad-R@20
Inline-citation-specific-R@20
Author-written-broad-R@20
Author-written-specific-R@20
Avg-broad-R@20
BM25
37.4
55.8
48.6
73.5
39.9
E5-large-v2
55.8
63.9
54.3
 75.8
55.4 

The results for splitting into sentence

model
Inline-citation-broad-R@20
Inline-citation-specific-R@20
Author-written-broad-R@20
Author-written-specific-R@20
Avg-broad-R@20
E5-large-v2
32.8
51.4
49.3
 65.8 
37.0 


First I try to merge the title, context, key_idea, method, outcome together, the result is:

model
Inline-citation-broad-R@20
Inline-citation-specific-R@20
Author-written-broad-R@20
Author-written-specific-R@20
Avg-broad-R@20
BM25
41.3
59.3
54.3
72.9
44.3
E5-large-v2
53.7
64.9
57.1
 74.9
54.5 

Then I try to split 5 aspects, the result is:

model
Inline-citation-broad-R@20
Inline-citation-specific-R@20
Author-written-broad-R@20
Author-written-specific-R@20
Avg-broad-R@20
BM25
38.4
46.5
40
63.5
38.8
E5-large-v2
41.2
55.8
48.6
67.3
42.8




This time I use title&abstract, 4 aspects as five keys for a paper, result:

model
Inline-citation-broad-R@20
Inline-citation-specific-R@20
Author-written-broad-R@20
Author-written-specific-R@20
Avg-broad-R@20
BM25
37.3
51.9
60
71.1
42.4
E5-large-v2
45.4
62.7
51.4
 73.0
46.7 

