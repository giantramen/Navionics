# Navionics

Repo for cocoapods Navionics iOS framework so you can use Pod Navionics instead of dragging in the framework files manually. 


Insert this run script in build phases to copy the bundle automatically. 
cp -R -f $PROJECT_DIR/Pods/Navionics/NavionicsMobileSDK.framework/NavionicsMobileSDK.bundle $BUILT_PRODUCTS_DIR/$CONTENTS_FOLDER_PATH/
