# Queer HCI SLR Dataset

This repository contains the dataset described in "Cruising Queer HCI on the DL: A Literature Review of LGBTQ+ People in HCI" (https://doi.org/10.1145/3613904.3642494)

Our dataset is a CSV with the following features:

1. Year (int)
    1. Submission publication year
1. Code (int)
    1. A number between 0 and 4  (inclusive) representing the degree to which a paper in our corpus related to LGBTQ+ people, per the scale in our paper
1. Author (str)
    1. A semi-colon separated list of author names
1. Title (str)
    1. Submission title
1. Url (str)
    1. The doi associated with each submission
1. Venue (str)
    1. One of {CHI, CSCW, DIS, TOCHI}, representing the venue a paper was published in
