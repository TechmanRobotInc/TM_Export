# __TM ROS Driver vs TMflow software Usage__

For TM Plug&Play supported items of TMflow software, users do not need to write additional programs or dig into technical documents of both parties before integrating, but import the software package to use in TMflow directly. Place the downloaded component in the folder named TM_Export in root directory of a USB drive labeled with TMROBOT. Insert the USB drive into to Control Box and navigate to &rArr;  System &rArr; Import/Export to import the component onto the robot.

## __Import Data Table Setting__
Insert the flash drive to the Techman Robot Control Box before using the function.
To use the Import function: Click on the Import button at the top left, select the robot of the data source in the flash drive from the robot list, and then select the desired data from the Select file box. Click an item in this box to add the item to the Selected files box. After completing the new addition, click Import at the bottom right to start the Import procedure.

### &sect; Update files from the git repository
>To download and unzip the update files, then place all the content generated from the unzipped files, or directly clone the the TM driver of git repository into the root directory of the USB flash drive labeled with __TMROBOT__ by typing<br/>
``git clone https://github.com/TechmanRobotInc/TM_Export.git``<br/>
>
> ![Usb_Label_Name_TMROBOT.png](figures/Usb_Label_Name_TMROBOT.png)
### &sect; Insert the USB flash drive to the Control Box

> Mouse-click to enter the page of __System &rArr; Import/Export__ in order.<br/>  
> 1.Click Import on the top left, then select to apply the imported setting ``TMROS_EthSlave`` in the Robot List prompted and click OK.<br/>
> 2.Click to select the project ``Ethernet Slave`` to import in the Import Project List prompted.<br/>
> 3.Click to select the name ``Data_Table_Setting_TM_ROS_Default`` of the setting listed in Selected Files.<br/>
> 4.Click Import at the bottom right to import the setting.<br/>
>
> ![Import_TMROS_EthSlave.png](figures/Import_TMROS_EthSlave.png)
### &sect; Transmit the __Ethernet Slave Data Table__ TM ROS default settings
> After importing, mouse-click to enter the page of __Setting &rArr; Connection &rArr; Ethernet Slave__ in order.<br/> 
>
> 1.On ``Ethernet Slave`` setting page, let Data Table Setting STATUS : Disable, then click ``Data Table Setting`` to enter the next page.<br/>
> 2.On ``Receive/Send Data Table Setting`` setting page, click ``Open`` to select files of the setting listed in Transmit File List prompted.<br/>
> 3.Select the file name ``Data_Table_Setting_TM_ROS_Default`` in the Transmit File List prompted and click OK.<br/>
> 4.Return to ``Ethernet Slave`` setting page, enable the `Data Table Setting` item to STATUS : Enable.<br/>
>
> ![Import_TMROS_Data_Table_Setting.png](figures/Import_TMROS_Data_Table_Setting.png)
> You have completed the predefined TM ROS default project to receive/send specific data. 

