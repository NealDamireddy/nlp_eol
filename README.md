# nlp_eol
# Cyber security vulnerability categorization using NLP
Cyber Security scanners like Qualys, Nexpose etc publish their tests(aka plugins) to their customers. Some of these plugins test the presence of an outdated/EOL(end of life) software version/product. These outdated versions typically have security vulnerabilities where the software author/vendors have ceased support making them prime targets for cyber attacks by hackers. These plugins might not be explicitly categorized by the source scanner as such. The goal of this project is to categorize these plugins as EOL(or not) so users could *priortize* remediating these prior to others and avoid being compromised.

# Steps to run the code 
- Import the `src/*.ipynb` file into Google Colab
- Import/Upload the `src/eol/*` folder into your Google Drive and replace the path in the above notebook file.
`filepath = '/content/drive/MyDrive/Neal/DataScience/eol'`
- Run the notebook on Colab, this might require providing permission for Colab to access your Google Drive folder

# Methodology and Models
- Supervised learning
- word2vec
- nltk: stopwords,punkt,lemmatizer
- Bag Of Words(BOW) with Trigrams
- Logistical regression

# Goal was to learn basics of datascience, nlp and have fun!

# Authors
- Nilai(Neal) Damireddy
- Clayton Greenberg

# Journal Publish
- JSR.org(https://jsr.org): Submission ID: 2102
  
# References
![image](https://github.com/alokrep/npl_eol/assets/3209293/5d4a0776-b696-48bb-87fe-59e36408d695)
