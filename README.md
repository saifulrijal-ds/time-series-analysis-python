# time-series-analysis-python

Repositori ini berisi catatan belajar saya dan beberapa latihan yang telah disediakan dari kursus [Python for Time Series Data Analysis](https://www.udemy.com/share/101WWMAEMad15SRX8D/). Pekerjaan masih dalam progres. 

Jika anda ingin mencoba menjalankan kode di dalam notebook saya merekomendasikan menggunakan anaconda environment dengan konfigurasi pada tsa_course_env.yml yang disediakan oleh kursus. 

**Perlu diperhatikan** pada tsa_course_env.yml Pandas yang digunakan adalah pandas=0.23.4 sedangkan versi anaconda terupdate pandas=1.2.0, perbedaan hasil terjadi pada penggunaan ```pandas.DataFrame.plot.bar()``` untuk plotting dengan nilai baris x berupa data dengan tipe datetime. Perbedaan terlihat seperti pada dokumentasi [bar plot pandas 0.23.x](https://pandas.pydata.org/pandas-docs/version/0.23/generated/pandas.DataFrame.plot.bar.html) dan [bar plot pandas 1.2.0](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.bar.html) pada bagian paling bawah halaman, plotting "lifespan".

---

This repository contains my study notes and some of the exercises provided from the [Python for Time Series Data Analysis] course (https://www.udemy.com/share/101WWMAEMad15SRX8D/). Work is still in progress. 

If you want to try running the code in a notebook I recommend using the anaconda environment with the configuration in the tsa_course_env.yml provided by the course. 

**Please note** on tsa_course_env.yml Pandas used is pandas=0.23.4 while the updated anaconda is pandas=1.2.0, the difference in results occurs when using ```pandas.DataFrame.plot.bar ()``` for plotting with value axis x in the form of data with datetime type. The differences are seen in the documentation [pandas plot bar 0.23.x](https://pandas.pydata.org/pandas-docs/version/0.23/generated/pandas.DataFrame.plot.bar.html) and [pandas plot bar 1.2 .0](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.bar.html) at the very bottom of the page, plotting "lifespan".
