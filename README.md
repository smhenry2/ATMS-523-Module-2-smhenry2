# ATMS-523-Module-2

## Description

Module 2 notebooks and assignment by Sarah Henry.

## Usage

Install required libraries using the `environment.yml` file.  `mamba install environment.yml` then mamba activate `xarray-climate`.

The Homework assignment can be completed in a new jupyter notebook that you commit to this repository.

The examples from lecture 3 and 4 are here also.

Make sure you install software as we did in the check in:
   ```bash
   mamba env create --prefix $HOME/envs/xarray-climate -f environment.yml
   mamba activate $HOME/envs/xarray-climate
   ```
   or with pip:
   ```bash
   python -m venv .venv && source .venv/bin/activate
   pip install -r requirements.txt
   ```

   and use this environment when running the codes and for your homework.


## References

Hersbach, H., and Coauthors, 2020: The ERA5 global reanalysis. Quarterly Journal of the Royal Meteorological Society, 146, 1999–2049, https://doi.org/10.1002/qj.3803.

## License

[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)