# IoT_mud_files_locations
 We generate MUD files from captures of 31 IoT devices (plugs, cameras, bulbs), activities at 13 countries, using MUDGEE. The resulted MUD files (per countries) are available at the repo.
% Please add the following required packages to your document preamble:
% \usepackage{multirow}
\begin{table}[ht]
\begin{tabular}{|l|l|l|l|}
\hline
\textbf{Device} &
  \textbf{Functionality} &
  \textbf{Device Locations} &
  \textbf{Type} \\ \hline
\textbf{Sousvide} &
  \begin{tabular}[c]{@{}l@{}}Power on,\\ Power off\end{tabular} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
  Appliances \\ \hline
\textbf{\begin{tabular}[c]{@{}l@{}}Amazon\\ echoplus\end{tabular}} &
  \multirow{4}{*}{\begin{tabular}[c]{@{}l@{}}Power on,\\ Power off,\\ Volume control,\\ Voice commands\end{tabular}} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
  \multirow{4}{*}{Audio} \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Amazon\\ echospot\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Amazon\\ echodot\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Google \\ home mini\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \hline
\textbf{Blink camera} &
  \multirow{6}{*}{\begin{tabular}[c]{@{}l@{}}Power on,\\ Power off,\\ Movement,\\ Record video,\\ Take picture\end{tabular}} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
  \multirow{6}{*}{Camera} \\ \cline{1-1} \cline{3-3}
\textbf{Wansview cam} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Ring doorbell} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Yi camera} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Yi camera} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States,\\ Hong Kong, \\ Australia,\\ France,\\ Germany,\\ Mexico, \\ India,\\ Russia\end{tabular} &
   \\ \cline{1-1} \cline{3-3}   
\textbf{Xiaomi camera} &
   &
  \begin{tabular}[c]{@{}l@{}}United States,\\ China, \\ Israel\end{tabular} &
   \\ \hline
\textbf{xiaomi cleaner} &
  \multirow{9}{*}{\begin{tabular}[c]{@{}l@{}}Power on,\\  Power off,\\  Change brightness,\\  Change temperature,\\  Change color\end{tabular}} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
 \multirow{9}{*}{\begin{tabular}[c]{@{}l@{}}Home \\ Automation\end{tabular}} \\ \cline{1-1} \cline{3-3}
\textbf{T-wemo plug} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Tplink plug} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Tplink plug} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States,\\ Hong Kong\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Tplink bulb} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Nest T-stat} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Magichome\\  strip\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Xiaomi \\ light bulb\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}Spain,\\ Russia,\\ India,\\ Brazil,\\ Australia,\\ Antarctica,\\ Argentina,\\ United Kingdom,\\ United States,\\ Hong Kong\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Lifx light bulb} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States,\\ Hong Kong\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
 \hline
\textbf{\begin{tabular}[c]{@{}l@{}}Samsung \\ smart-things\\ hub\end{tabular}} &
  \multirow{7}{*}{\begin{tabular}[c]{@{}l@{}}Power on,\\ Power off,\\ Change brightness,\\ Change color,\\ Change temperature\end{tabular}} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
  \multirow{7}{*}{Smart Hub} \\ \cline{1-1} \cline{3-3}
\textbf{Lightify hub} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Philips hub} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{\begin{tabular}[c]{@{}l@{}}Blink \\ security hub\end{tabular}} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Xiaomi-hub} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Sengled-hub} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Insteon-hub} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \hline
\textbf{Appletv} &
  \multirow{4}{*}{\begin{tabular}[c]{@{}l@{}}Power on,\\ Power off,\\ Voice commands,\\ Change Volume\end{tabular}} &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
  \multirow{4}{*}{TV} \\ \cline{1-1} \cline{3-3}
\textbf{Roku-tv} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Firetv} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \cline{1-1} \cline{3-3}
\textbf{Samsung tv} &
   &
  \begin{tabular}[c]{@{}l@{}}United Kingdom,\\ United States\end{tabular} &
   \\ \hline
\end{tabular}
\caption{IoT devices in our dataset, totally 31 devices in 12 different device locations.
Note to mention that two devices appears both in our dataset and in \cite{ren2019information}, we present them as two separate devices since they have different firmware versions and different network captures.}
\label{tab:devices_locations}
\end{table}
