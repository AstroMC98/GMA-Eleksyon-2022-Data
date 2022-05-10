<!-- HEADER -->
# GMA-ScrapER-2022
This jupyter notebook downloads batch data from `https://www.gmanetwork.com/news/eleksyon2022` by inspecting and appending json responses of the backend API. The script is limited by the batch number which is irregularly updated. Granularity of the retrieved data is up to barangay-level at specific batches. Heirarchy of the scraped data is as follows : `Region -> Province -> Municipality -> Result Batch`).  

Feel free to fork and optimize the code even further. 

<!-- DEPENDENCIES -->
## Dependencies

* python-requests
* tqdm

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

Marc Castro - https://github.com/AstroMC98

Project Link: [https://github.com/AstroMC98/GMA-Eleksyon-2022-Data](https://github.com/AstroMC98/GMA-Eleksyon-2022-Data)

<!-- ACKNOWLEDGMENTS -->
## Notes

Data was compiled from the official Eleksyon 2022 page of GMA (https://www.gmanetwork.com/news/eleksyon2022) as of `12:00PM May 10 2022`. Accuracy and legitimacy of the collected data may be verified through the same cited webpage.
