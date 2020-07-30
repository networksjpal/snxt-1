# snxt
Package 'snxt' contains functions frequently used at the JPAL networks lab. It contains the following functions (readme updated on 30th July 2020)

1. pull_data - This function uses the api provided by surveycto to download data directly to R. Only datasets (either encrypted or un-encrypted) can be downloaded with the current version as we don't collect media in our form responses.
2. vc_open - This function opens veracrypt container from within R. This integrates veracrypt with R so the entire workflow can be managed directly from within R.
