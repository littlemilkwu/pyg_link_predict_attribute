# Dataset

## content
* node_id
* attributes
    + 1: if the attribute is True
    + 0: if the attribute is False

## train.csv
* edge_id
* to
* from
    + where "to" is pointed by "from" (to <-- from)
* label
    + 1: if the edge is linked
    + 0: if the edge is not linked

## test.csv
* edge_id
* to
* from

## upload.csv
* edge_id
* probability

# Evaluate
* AUC: area under ROC curve
* AP: average precision
