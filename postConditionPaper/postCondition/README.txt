This folder contains resources described in the paper:
“A Spousal Relation Begins with a Deletion of engage and Ends with an Addition of divorce”: Learning State Changing Verbs from Wikipedia Revision History

(1) learned verbs that predict state changes: 
    (a) learnedVerbs.txt (MaxEnt + feature selection using MIP) 
    (b) learnedVerbsWithoutFS.txt (MaxEnt)

    FORMAT of each line: 
    state_change <tab> verb_1 <comma> feature_weight_1 <semicolon> verb_2 <comma> feature_weight_2 <semicolon> ...

    The verbs are ordered by weights from highest to smallest.


(2) data curated from Wikipedia revision history for learning about verbs and state changes:
    sample-wiki-rev-history.txt

    (NOTE: only include a 100-lines sample of the data here as it is too big to include as a submission resource)
    
    The original file contains 288,184 lines, each a difference between two Wikipedia page revisions.
    The data is obtained from Wikipedia revision histories of 16,909 persons in Wikipedia.

    FORMAT of each line:
    entity_name <tab> entity_wiki_url <tab> start_revision_date <tab> end_revision_date <tab> html_content_of_difference_between_the_two_revisions

