# Generate web optimized images

With this plugin, we can generate web optimized images as well as their Internal Overviews and Virtual File.

Used python packages

PyQt5: To develop an interactive QGIS Plugin

PyqtSignal: To emit and receive signals between threads and main thread

QThread: Threading was used so that the plugin main window won’t freeze while executing the processing algorithm.

QMessageBox: Display message box as soon as the plugin has finished processing.

QProgressBar: Show the processing progress.

Gdal: Apply the tiles compression, overviews and .vrt file creation. 

Glob: Loop through the *.tif files in a folder.

Datetime: Add date and time to the log box.

