# Readings

## linear algebra
http://cs229.stanford.edu/section/cs229-linalg.pdf

## probability
http://cs229.stanford.edu/section/cs229-prob.pdf

## convex optimization
http://cs229.stanford.edu/section/cs229-cvxopt.pdf
http://cs231n.github.io/optimization-2/
http://cs231n.github.io/linear-classify/#softmax
http://peterroelants.github.io/posts/neural_network_implementation_intermezzo02/

## numpy
http://cs231n.github.io/python-numpy-tutorial/

## word2vec
http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/
http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf
https://arxiv.org/pdf/1301.3781.pdf
http://nlp.stanford.edu/pubs/glove.pdf
http://www.aclweb.org/anthology/Q15-1016
http://www.aclweb.org/anthology/D15-1036
https://www.tensorflow.org/tutorials/word2vec/
http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/


## neural net
http://peterroelants.github.io/posts/neural_network_implementation_part01/
http://peterroelants.github.io/posts/neural_network_implementation_intermezzo01/
http://peterroelants.github.io/posts/neural_network_implementation_part02/
http://peterroelants.github.io/posts/neural_network_implementation_part03/
http://peterroelants.github.io/posts/neural_network_implementation_intermezzo02/
http://peterroelants.github.io/posts/neural_network_implementation_part04/
http://peterroelants.github.io/posts/neural_network_implementation_part05/

https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/


http://cs231n.github.io/neural-networks-1/
http://cs231n.github.io/optimization-2/
http://u.cs.biu.ac.il/~yogo/nnlp.pdf




# Set up virtual env
```
 virtualenv -p /usr/bin/python2.7 venv
 source venv/bin/activate
 pip install -r requirements.txt
```

# Get data
```
./get_datasets.sh
```



To submit the written portion of the assignment:
Log into Gradescope with your Stanford email address. You should have received an email with your login details. If you didn't, please let us know right away.
Upload your pdf.
Make sure to select pages for all problems. For coding questions, you may select a blank or random page.
Please submit your report only through Gradescope. We will be unable to accept your report if it is submitted via AFS.
 
To submit the coding portion:
If your assignment directory (code) is not on myth or corn machines, first copy your files over using the following command:
scp -r <assignment_directory> <sunet_id>@(myth/corn).stanford.edu:<destination_path>
Once you're logged into myth or corn, step into your assignment directory and execute the following commands:
make submit
This generates your submission zip file in the assignment directory. You MUST perform this step.
/afs/ir.stanford.edu/class/cs224n/submit



q4_sentiment.py --pretrained
=== Recap ===
Reg		Train	Dev	Test
1.00E-02	39.934	36.240	37.195
2.00E-02	39.841	36.603	37.240
3.00E-02	39.853	36.331	37.330
4.00E-02	39.864	36.331	37.466
5.00E-02	39.899	36.331	37.511
6.00E-02	39.864	36.331	37.376
7.00E-02	39.853	36.331	37.195
8.00E-02	39.841	36.421	37.240
9.00E-02	39.864	36.331	37.240
1.00E-01	39.806	36.240	37.149