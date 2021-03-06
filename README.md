# Freesound_Max-MSP_Modules

![alt text](https://user-images.githubusercontent.com/14850001/30143594-f66b6a30-9386-11e7-9041-02f47b02713b.png)


(PS : Library is still under development)


Client-side library for interacting with freesound API from Max/MSP using native max js object.

These reusable Max patches encapsulates different search functionalities of Freesound API.

Visit http://www.freesound.org/docs/api/ 

This project uses Stepfan Brunner's implementation of OAuth2 authorisation of freesound API in Max.
http://stb.klingt.org/ElevatorMusicGenerator/

And some visualizing concepts from Nao Tokui's 'freesound_search' max external.
https://github.com/naotokui/MaxMSP_Objects/tree/master/freesoundsearch

Thanks to Stefan Brunner and Nao Tokui.


## Installation 

1. Apply for API key at http://www.freesound.org/apiv2/apply 

2. Replace respective fileds in the "api_auth.json" file inside the 'data' folder with your CLIENT_ID & CLIENT SECRET (API_KEY).

3. Create a folder named 'freesound_download' in your system home directory (/) of your computer. You are expected to change the file path and workflow inside '/code/download_by_id.js' inorder to download sound samples in a different folder.

4. Load the max project file 'Freesound_Modules_Max.maxproj' located in the home folder and follow the instructions in the patch.


## Contributing
1. Fork the repo!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

Enjoy Freesounding !

-------------------------
In case of any doubts or suggestions contact me at albinandrew.correya@upf.edu










