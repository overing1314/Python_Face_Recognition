Overview
********

#. Requirement:

   .. code-block:: bash

      sudo apt-get update
	  sudo apt-get upgrade
	  sudo apt-get install libopencv-dev
	  pip3 install opencv-python == 3.4.3.18
	  pip3 install opencv-contrib-python == 3.4.3.18
	  pip3 install pandas
      pip3 install scikit-image
      pip3 install dlib
      git clone https://github.com/coneypo/Dlib_face_recognition_from_camera


#. Install some python packages needed

   .. code-block:: bash

      pip3 install opencv-python
      pip3 install scikit-image
      pip3 install dlib
      git clone https://github.com/coneypo/Dlib_face_recognition_from_camera

#.  Register faces 

   .. code-block:: bash

      python3 get_face_from_camera.py

#.  Features extraction and save into "features_all.csv"

   .. code-block:: bash

      python3 features_extraction_to_csv.py

#.  Real-time face recognition

   .. code-block:: bash

      python3 face_reco_from_camera.py

#.  Real-time face recognition with OT

   .. code-block:: bash

      python3 face_reco_from_camera_ot_single_person.py
      python3 face_reco_from_camera_ot_multi_people.py

