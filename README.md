# Which Rules Entail this Fact? <br> An Efficient Approach Using RDBMSs
Tim Gutberlet (tim.gutberlet@students.uni-mannheim.de) & Janik Sauerbier (janik.sauerbier@students.uni-mannheim.de)

## Summary
Knowledge graphs (KGs) are used to store information about relationships between real-world entities in various fields. Learned rules over KGs describe patterns of KGs and allow for knowledge inference. In this paper, we focus on the problem of identifying all rules that entail a certain target fact given a KG and a set of previously learned rules. This can enable link prediction as well as help explain connections between rules and (potential) facts. Solving this problem time-efficiently for large rulesets and KGs is a challenge. To tackle this challenge, we propose an approach relying solely on RDBMSs including indexing, filtering and pre-computing methods. Our experiments demonstrate the efficiency of our approach and the effect of various optimizations on different datasets like YAGO3-10, WN18RR and FB15k-237 using rules learned by the bottom up rule learner AnyBURL.

## Folder structure

### Code
This folder contains the codebase for relevant software (e.g., AnyBURL) as well as experimental scripts and databases created throughout our project.

### Meeting Notes
This folder contains all Meeting Notes including the aganda and resulting ToDo's within the context of the project.

### Paper
The final paper, first drafts and LaTeX files.
