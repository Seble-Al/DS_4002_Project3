# DS_4002_Project3

Authors: Seble Alemu (cnd3ru@virginia.edu), Janna Serrao	(jhs5gq@virginia.edu), Ethan Ogilvie (ebo4dq@virginia.edu)

Project Topic: Using an artificial neural network to classify European artwork from the late 1900s into the categories of "drawing" or "painting"
<h2>Section 1: Software and Packages</h2>
<b>Software:</b> Rivanna OnDemand or Vscode <br>
<b>Platform:</b> Jupyter Notebook<br>
<b>Packages:</b> you will need to install the following packages if they are not already available
 <table>
  <tr>
    <th>Package</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>numpy</td>
    <td>math operations, store data as an array</td>
  </tr>
  <tr>
    <td>pandas</td>
    <td>clean + process + explore data</td>
  </tr>
   <tr>
    <td>json</td>
    <td>to read json data files</td>
  </tr>
   <tr>
    <td>matplotlib</td>
    <td>create plots</td>
  </tr>
   <tr>
    <td>json</td>
    <td>read from json files</td>
  </tr>
  <tr>
    <td>requests</td>
    <td>make API requests</td>
  </tr>
  <tr>
    <td>PIL</td>
    <td>load and process image data in python</td>
  </tr>
  <tr>
    <td>io</td>
    <td>load an image data given an image url</td>
  </tr>
  <tr>
    <td>torchvision</td>
    <td>prepare image data to be used in convolutional neural network</td>
  </tr>
  <tr>
    <td>torch</td>
    <td>run convolutional neural networks</td>
  </tr>
  <tr>
    <td>tqdm</td>
    <td>have a progress meter for iterable functions</td>
  </tr>
  <tr>
    <td>time</td>
    <td>temporal regulation of iterative function run times</td>
  </tr>
  <tr>
    <td>sklearn</td>
    <td>create plots</td>
  </tr>
  <tr>
    <td>tensorflow</td>
    <td>plot and analyze image data</td>
  </tr>
</table> 

<h2>Section 2: Documentation Tree (WIP)</h2>

View via <a href = "https://miro.com/app/board/uXjVLk8cn0k=/?share_link_id=967850119871">this link! </a>

<h2>Section 3: Instructions to Reproduce Results</h2>

1. Download Needed Scripts and Data:

Create a folder in your hard drive to store files locally for this project (a suggested folder name is “met_data”). Once the folder is made, go to the DATA folder of this repository and download dr_19th.csv and pt_19th.csv. 

  
2. Running the Analysis script.

Go to the SCRIPTS folder from this repository. Download the file [SCRIPTS/proj_3_model_creation.ipynb] and save to the custom folder you created for this project. Open the file in your choice code editing software (we recommend using Vscode or using UVA Rivanna OnDemand to run Jupyter Notebook). Take note of libraries you may not have installed, they are listed in the first code chunk.  See the table above for the names of the necessary packages to install. Once libraries are installed, run the first code chunk to make sure you have all libraries needed. Make sure the filepath matches the path saved locally on your computer. After you have checked this, run the next code chunk, as well as the rest of the code chunks in the file. 

As results load, take time to review the comments in the code to understand each step. At the end of the file are the figures, which you can find blown up as individual images in the OUTPUT folder of this repository.

To understand how the final dataset and model was formed, look at the other files in the SCRIPTS folder. 

3. Review the Results

You can evaluate the success of your results by checking the figures produced with those stored in the OUTPUT folder. If you are confused by the variables analyzed in the final predictor model results, which only came from review dataset, please check the Data Appendix in the DATA folder.

Questions? Error messages? Concerns? Feel free to contact the authors! Our emails are found at the top of this file.

