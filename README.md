# Billboard-Artist-Frequency

Analysis covering the weekly Billboard Top 100 list, from 1958-08-09 to 2020-06-27, to highlight artists who frequent said lists more commonly as supporting (rather than main) artists. Historical song data was scraped from Billboard.com then parsed into multiple dataframes for later analysis and data visualization.

Note that 'df_unique.zip' will need to be extracted for the notebook to be run. This notebook was structured so as to replace the most time-consuming steps with imports of previously created dataframe / Excel files. Manual, execution of the entire notebook (re-execution of all steps, i.e. no relying on provided dataframe / Excel files), will require switching certain cells from 'raw' to 'code'. The above-mentioned full execution time is multiple hours, so buckle in and bring some popcorn.

The included infographic 'Billboard Artist Frequency.png' is composed of three key elements: a bar chart of most frequent supporting artists ranked in order of total main artist songs (top left), a treemap highlighting the delta between an artist's frequency as main and supporting artist (top right), and supporting artist frequency as a percentage of combined supporting and main artist frequency (bottom). The three artists who ranked in the Billboard Hot 100 the most as a supporting artist were Lil Wayne (90 songs), Nicki Minaj (70 songs), and Travis Scott (37 songs), whereas the top three artists with the highest percent of featuring songs compared to overall ranked songs were Jeremih (72.73% or 16/22), The Raiders (70.83% or 17/24), and T-Pain (67.39% or 31/46).

Rework on this project should be centered on how the main and supporting artists were parsed. Specifically, to better handle songs with multiple main artists.
