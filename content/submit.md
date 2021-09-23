# What can be published on NeuroLibre?

NeuroLibre currently welcomes submissions along two tracks:
 - **Tutorial** notebooks related to a workshop in the neuroscience field.
 - **Companion** notebooks for articles posted as preprints in the neuroscience field.
 
These notebooks are expected to use less than 100 GB disk space, and run in less of an hour, although exceptions may be granted on a case by case basis. Each user has 1CPU (up to 2 depending on the server workload) and 4GB RAM  (up to 6GB depending on the server workload), so your notebooks should be able to run under this configuration. If you need more ressources for a limited period, please open an issue on this repository.

# How are NeuroLibre submissions reviewed?

Submissions are not reviewed in the sense of a traditional scientific publications, but notebooks do undergo a technical review. The NeuroLibre team checks that the notebooks fit one of the two tracks above, run correctly, and that the text and code are readable. We also check how much compute time and data storage are required. NeuroLibre commits to provide computational resources for free, yet this investment must benefit substantially the open neuroscience community. The Neurolibre team reserves the right of rejecting a submission if the content of the notebook is judged to fall outside the neuroscience field, requires excessive resources for the proposed scope of work, or if the code or text are of unsufficient quality. Note that NeuroLibre purely reviews the technical aspects of the notebooks, and not the scientific content. As such, a NeuroLibre review complements, rather than replaces, the peer reviews offered by traditional scientific journals. Please read our [review guidelines](/2020/10/26/review-guidelines/) for more information.

# How to submit?

1. Create a public repository on [GitHub](https://github.com/) which will host the files.
2. Write a [Jupyter](https://jupyter.org/) notebook (`.ipynb`) containing all your work.
3. Create a `binder` folder which will contain all the dependencies :
> * A [requirements file](https://mybinder.readthedocs.io/en/latest/using/config_files.html#requirements-txt-install-a-python-environment) containing all the software dependencies.
> * A [data_requirement](https://github.com/SIMEXP/Repo2Data) file containing the data dependencies if needed.
4. Go to https://binder.conp.cloud.
5. Fill the repository name and save the given URL. This will be used to share your binder notebooks with others.
6. Click on `launch` and wait for the build. Please be patient, as the first build may take a long time depending on your setup. When your notebook loads, you are ready to publish on the neurolibre website!
7. [Create an issue](https://github.com/neurolibre/submit/issues/new?assignees=pbellec&labels=&template=submission.md&title=%5BSUBMISSION%5D) in this repository, using the "Submission" template, and fill in all the information. 
8. Our team will fork your repository on https://github.com/neurolibre. We will test that everything is working, and contact you using your github handle for any issue we identify. The issues will be open on our fork of the repo, and you will be expected to submit pull request to this fork to address any issue.
9. Once all issues have been addressed, the repository will be published on the [NeuroLibre website](http://neurolibre.conp.ca), and associated with a unique URL that can be shared publically.
 
Note that we expect all our community members to remain courteous and constructive at all times. Please read our [code of conduct](/2020/10/26/code-of-conduct/) for more information. You can contact editors privately through emails, or on the [mattermost brainhack forum](https://mattermost.brainhack.org) if you have any question, comment or complaint.

# Examples of NeuroLibre-ready repositories
 * https://github.com/neurolibre/boutiques-tutorial
 * https://github.com/ltetrel/binder-tuto
 * https://github.com/ltetrel/repo2data-caching-s3
 * https://github.com/ltetrel/binder-bash-intro
 * https://github.com/binder-examples/octave
 * https://github.com/ltetrel/binder-cpp
–
