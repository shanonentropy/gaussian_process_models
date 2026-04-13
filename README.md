# gaussian_process_models
In this project we are exploring GP models to map NV ODMR and PL spectra onto a thermodynamic variable of interest.
In published results GP (Matren kernel) do a good job of capturing ODMR spectra and mapping it on temp with unceratinty of > 1K 

Here we will testing out:

* diff kernels
* expanding to PL spectra
* using sparse GP, using latent represenation to fuse GP output with:
  * deep learning activations
  * ODMR with PL
 
