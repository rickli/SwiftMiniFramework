# SwiftMiniFramework
项目配置
Target->Building Setting-> Search Paths->Framework Search Paths添加$(PROJECT_DIR)/Carthage/Build/iOS
项目的Target-> Build Phases -> '+' -> New Run Script Phase:
- 添加脚本/usr/local/bin/Carthage copy-frameworks
- 添加"Input Files" $(SRCROOT)/Carthage/Build/iOS/XXXX.framework等
