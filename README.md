# Paper review: GENERanno
This project is here solely to ensure the reproducibility of the results presented in my review.   

I don't expect anyone to run this code. As a result, the code in this project is missing many features typically expected, such as documentation, comments, a test suite, cross-platform compatibility, and performance optimizations. I designed the code without any user-friendly features, such as meaningful error messages or system error checks.   

Code was developed and executed on an Ubuntu Linux system.   

---

Select a location for the project.  
Download the project from the repository.   
```
git clone https://github.com/Alex-Lomsadze/review_generanno.git
```
Add path to the project's bin folder.
```
export PATH=$PATH:/path_to_bin/
```
Download [two database files](https://huggingface.co/datasets/GenerTeam/cds-annotation/tree/main) from the GenerTeam site at Hugging Face: one with bacteria data and another with archaea:
```
download_GenerTeam_parguet.sh
```

