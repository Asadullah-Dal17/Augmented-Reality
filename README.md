# Augmented Reality

"ar.py" is a python program that uses OpenCV to render .obj files on Aruco markers. For an in-depth explanation, check out my [blog tutorial](https://medium.com/swlh/augmented-reality-diy-3fc138274561).

<!-- ![Demo](https://user-images.githubusercontent.com/31953115/121981314-0b712c00-cdab-11eb-98d4-decf737824ea.gif) -->

<p align = "center">
  <img src="https://user-images.githubusercontent.com/31953115/121981314-0b712c00-cdab-11eb-98d4-decf737824ea.gif" alt="animated" />
</p>


## Dependencies

It uses OpenCV(3.4.2) and Numpy(1.17.2). The python version is 3.7.5

Before installing the dependencies, it is recommended to create a virual environment to prevent confilcts with the existing environment. Using conda, 

```bash
conda create -n augmented_reality python=3.7.5
conda activate augmented_reality
``` 

To install the dependencies - 
```bash
pip install -r requirements.txt
```

## Usage
For the main program - 

```bash
python ar.py
```
It is recommended to print the aruco marker(data/m1.pdf) on a piece of paper. Alternatively, the program should work (but inferiorly) with the marker open on your phone. The white margin around the marker boundary is required for boundary detection. Keeping the marker flat (for example, by sticking it to a piece of cardboard) further helps in detecting the marker. 

For a faster version which uses the Lucas-Kanade method for tracking - 
```bash
python ar_with_tracking.py
```

(Optional) For camera calibration alter the path mentioned in the file and run - 

```bash
python camera_calib.py 
```

Refer to the blog for all the details about camera calibration. 
## 📫 Let's Connect

<div align=\"center\">

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@asadullah-dal)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/aiphile17)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/aiphile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ai_phile)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@aiphile)
[![Portfolio](https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=About.me&logoColor=white)](https://asadullah-dal17.github.io/asadullahdal.github.io)

### 💼 Freelance Platforms

[![Fiverr](https://img.shields.io/badge/Fiverr-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/asadullahdal482)
[![Kwork](https://img.shields.io/badge/Kwork-Freelance-black?style=for-the-badge&logo=kwork&logoColor=white)](https://kwork.com/user/asadullah92)

</div>

## 💬 Questions or Need Help?

If you have any questions or need help with the project, feel free to DM me on [Instagram](https://www.instagram.com/aiphile17)!

<a href="https://www.instagram.com/aiphile17">
    <img src="https://img.shields.io/badge/Instagram-purple?style=for-the-badge&logo=Instagram&logoColor=white" height=20  alt="Insta Badge"/>
  </a>

