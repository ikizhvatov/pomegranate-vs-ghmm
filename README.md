Performance and precision comparison of two packages implementing HMM functionality, in particular, the Baum-Welch algorithm.

See `pomegranate-vs-ghmm.ipynb` notebook for all the details.

Works only under python2.7 due to ghmm. The easiest way to install ghmm is from bioconda channel: `conda install -c bioconda ghmm`. For this reason, Windows is not (easily) supported, as there is no ghmm conda package for Windows. Use Linux or mac os.

Related pomegranate issue: https://github.com/jmschrei/pomegranate/issues/698
