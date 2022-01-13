## Import own python files in Google Colab
Steps:
1. Write any file.py and upload it to the Google Drive (Pereferably at: 'My Drive/Colab Notebooks)
2. Open Google Colab and mount google drive.
3. Write the gollowing line in a cell and execute
import sys
sys.path.insert(0,"/content/drive/My Drive/Colab Notebooks")
