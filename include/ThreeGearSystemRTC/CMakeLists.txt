set(hdrs ThreeGearSystemRTC.h HandTrackingClient.h HandTrackingListener.h HandTrackingMessage.h Threads.h ThreeGearBase.h
    PARENT_SCOPE
    )

install(FILES ${hdrs} DESTINATION ${INC_INSTALL_DIR}/${PROJECT_NAME_LOWER}
    COMPONENT library)

