# MP03 Comparative Reflection — Team 11

This project demonstrated that an analytics pipeline can generate important results when it is supported by well-designed and properly constructed search functions. At first, seeing zero mapped events might appear to be a failure or a sign that nothing relevant occurred in the industries we were analyzing. However, this initial outcome actually reveals something meaningful about the data itself and the filtering logic behind the pipeline.

A lack of results is not necessarily an absence of activity; rather, it can indicate that the search parameters are too narrow or not fully aligned with the terminology used in real-world event descriptions. Using this insight, we revisited and expanded our search phrases to include additional variations and alternative word choices that companies might use when describing similar events.

For example, in the Travel and Hospitality category, we originally searched for phrases like “new hotel.” To broaden the coverage, we added terms such as “new resort,” “new location,” and other related expressions that capture the same type of expansion but may be phrased differently by different organizations. A similar approach was used with Financial Services. Initially, we only looked for phrases like “new branch,” which limited the number of detected events.

By including additional terms such as “new facility,” “facility upgrade,” or “expansion,” we were able to capture a far wider range of business activities—anything that signaled growth, improvement, or investment within the industry. Once these expanded search terms were added, the number of qualifying events increased dramatically. In Financial Services, the total rose from just 1 event to 38. In Travel and Hospitality, the number increased from 3 to 11. These results reinforce how much impact thoughtful search-phrase design can have on the pipeline’s effectiveness.

Therefore, an empty map should not be interpreted as evidence that nothing happened. Instead, it highlights the limitations of the initial search logic. After refining and expanding the search phrases, the map became populated with markers representing events that fit the criteria. This demonstrates that iterative refinement is essential for any data-driven analytics workflow.

## Attribution

Team 11: Swikriti KC (Financial Services Pipeline Lead), Imran Aslam (Travel and Hospitality Pipeline Lead), Gabriel Asimakopoulos (Comparison and Visualization Lead / Integrator).
