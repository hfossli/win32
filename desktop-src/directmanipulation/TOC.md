# [Direct Manipulation](direct-manipulation-portal.md)
## [Viewports and content](directmanipulation-viewports-and-content.md)
## [Using multiple viewports in DirectManipulation](directmanipulation-multiple-vieports.md)
## [Processing input with DirectManipulation](directmanipulation-processing-input-with-directmanipulation.md)
## [Composition engine](directmanipulation-composition-engine.md)
## [Direct Manipulation Reference](direct-manipulation-reference.md)
### [Direct Manipulation Constants](direct-manipulation-constants.md)
### [Direct Manipulation GUIDs](direct-manipulation-guids.md)
### [Direct Manipulation Enumerations](direct-manipulation-enumerations.md)
#### [DIRECTMANIPULATION_AUTOSCROLL_CONFIGURATION](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_autoscroll_configuration?branch=dev)
#### [DIRECTMANIPULATION_CONFIGURATION](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_configuration?branch=dev)
#### [DIRECTMANIPULATION_DRAG_DROP_CONFIGURATION](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_drag_drop_configuration?branch=dev)
#### [DIRECTMANIPULATION_DRAG_DROP_STATUS](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_drag_drop_status?branch=dev)
#### [DIRECTMANIPULATION_GESTURE_CONFIGURATION](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_gesture_configuration?branch=dev)
#### [DIRECTMANIPULATION_HITTEST_TYPE](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_hittest_type?branch=dev)
#### [DIRECTMANIPULATION_HORIZONTALALIGNMENT](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_horizontalalignment?branch=dev)
#### [DIRECTMANIPULATION_INPUT_MODE](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_input_mode?branch=dev)
#### [DIRECTMANIPULATION_INTERACTION_TYPE](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_interaction_type?branch=dev)
#### [DIRECTMANIPULATION_MOTION_TYPES](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_motion_types?branch=dev)
#### [DIRECTMANIPULATION_SNAPPOINT_COORDINATE](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_snappoint_coordinate?branch=dev)
#### [DIRECTMANIPULATION_SNAPPOINT_TYPE](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_snappoint_type?branch=dev)
#### [DIRECTMANIPULATION_STATUS](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_status?branch=dev)
#### [DIRECTMANIPULATION_VERTICALALIGNMENT](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_verticalalignment?branch=dev)
#### [DIRECTMANIPULATION_VIEWPORT_OPTIONS](/windows/win32/content/directmanipulation/ne-directmanipulation-directmanipulation_viewport_options?branch=dev)
### [Direct Manipulation Interfaces](direct-manipulation-interfaces.md)
#### [IDirectManipulationAutoScrollBehavior](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationautoscrollbehavior?branch=dev)
##### [SetConfiguration method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationautoscrollbehavior-setconfiguration?branch=dev)
#### [IDirectManipulationCompositor](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationcompositor?branch=dev)
##### [AddContent method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcompositor-addcontent?branch=dev)
##### [Flush method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcompositor-flush?branch=dev)
##### [RemoveContent method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcompositor-removecontent?branch=dev)
##### [SetUpdateManager method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcompositor-setupdatemanager?branch=dev)
#### [IDirectManipulationCompositor2](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationcompositor2?branch=dev)
##### [AddContentWithCrossProcessChaining method](/windows/win32/content/directmanipulation/nf-directmanipulation-idirectmanipulationcompositor2-addcontentwithcrossprocesschaining?branch=dev)
#### [IDirectManipulationContent](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationcontent?branch=dev)
##### [GetContentRect method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-getcontentrect?branch=dev)
##### [GetContentTransform method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-getcontenttransform?branch=dev)
##### [GetOutputTransform Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-getoutputtransform?branch=dev)
##### [GetTag Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-gettag?branch=dev)
##### [GetViewport Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-getviewport?branch=dev)
##### [SetContentRect method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-setcontentrect?branch=dev)
##### [SetTag Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-settag?branch=dev)
##### [SyncContentTransform method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationcontent-synccontenttransform?branch=dev)
#### [IDirectManipulationDeferContactService](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationdefercontactservice?branch=dev)
##### [CancelContact method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdefercontactservice-cancelcontact?branch=dev)
##### [CancelDeferral method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdefercontactservice-canceldeferral?branch=dev)
##### [DeferContact method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdefercontactservice-defercontact?branch=dev)
#### [IDirectManipulationDragDropBehavior](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationdragdropbehavior?branch=dev)
##### [SetConfiguration method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdragdropbehavior-setconfiguration?branch=dev)
##### [GetStatus method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdragdropbehavior-getstatus?branch=dev)
#### [IDirectManipulationDragDropEventHandler](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationdragdropeventhandler?branch=dev)
##### [OnDragDropStatusChange method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationdragdropeventhandler-ondragdropstatuschange?branch=dev)
#### [IDirectManipulationFrameInfoProvider](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationframeinfoprovider?branch=dev)
##### [GetNextFrameInfo Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationframeinfoprovider-getnextframeinfo?branch=dev)
#### [IDirectManipulationInteractionEventHandler](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationinteractioneventhandler?branch=dev)
##### [OnInteraction method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationinteractioneventhandler-oninteraction?branch=dev)
#### [IDirectManipulationManager](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationmanager?branch=dev)
##### [Activate Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-activate?branch=dev)
##### [CreateContent Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-createcontent?branch=dev)
##### [CreateViewport Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-createviewport?branch=dev)
##### [Deactivate Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-deactivate?branch=dev)
##### [GetUpdateManager Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-getupdatemanager?branch=dev)
##### [ProcessInput Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-processinput?branch=dev)
##### [RegisterHitTestTarget method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager-registerhittesttarget?branch=dev)
#### [IDirectManipulationManager2](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationmanager2?branch=dev)
##### [CreateBehavior method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager2-createbehavior?branch=dev)
#### [IDirectManipulationManager3](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationmanager3?branch=dev)
##### [GetService method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationmanager3-getservice?branch=dev)
#### [IDirectManipulationPrimaryContent](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationprimarycontent?branch=dev)
##### [GetCenterPoint method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-getcenterpoint?branch=dev)
##### [GetInertiaEndTransform method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-getinertiaendtransform?branch=dev)
##### [SetHorizontalAlignment method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-sethorizontalalignment?branch=dev)
##### [SetSnapCoordinate method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setsnapcoordinate?branch=dev)
##### [SetSnapInterval method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setsnapinterval?branch=dev)
##### [SetSnapPoints method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setsnappoints?branch=dev)
##### [SetSnapType method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setsnaptype?branch=dev)
##### [SetVerticalAlignment method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setverticalalignment?branch=dev)
##### [SetZoomBoundaries method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationprimarycontent-setzoomboundaries?branch=dev)
#### [IDirectManipulationUpdateHandler](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationupdatehandler?branch=dev)
##### [Update Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationupdatehandler-update?branch=dev)
#### [IDirectManipulationUpdateManager](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationupdatemanager?branch=dev)
##### [RegisterWaitHandleCallback Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationupdatemanager-registerwaithandlecallback?branch=dev)
##### [UnregisterWaitHandleCallback Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationupdatemanager-unregisterwaithandlecallback?branch=dev)
##### [Update Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationupdatemanager-update?branch=dev)
#### [IDirectManipulationViewport](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationviewport?branch=dev)
##### [Abandon method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-abandon?branch=dev)
##### [ActivateConfiguration Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-activateconfiguration?branch=dev)
##### [AddConfiguration Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-addconfiguration?branch=dev)
##### [AddContent Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-addcontent?branch=dev)
##### [AddEventHandler Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-addeventhandler?branch=dev)
##### [Disable Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-disable?branch=dev)
##### [Enable Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-enable?branch=dev)
##### [GetPrimaryContent Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-getprimarycontent?branch=dev)
##### [GetStatus Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-getstatus?branch=dev)
##### [GetTag Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-gettag?branch=dev)
##### [GetViewportRect method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-getviewportrect?branch=dev)
##### [ReleaseAllContacts method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-releaseallcontacts?branch=dev)
##### [ReleaseContact method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-releasecontact?branch=dev)
##### [RemoveConfiguration Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-removeconfiguration?branch=dev)
##### [RemoveContent Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-removecontent?branch=dev)
##### [RemoveEventHandler Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-removeeventhandler?branch=dev)
##### [SetChaining Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setchaining?branch=dev)
##### [SetContact method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setcontact?branch=dev)
##### [SetInputMode Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setinputmode?branch=dev)
##### [SetManualGesture method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setmanualgesture?branch=dev)
##### [SetTag Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-settag?branch=dev)
##### [SetUpdateMode method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setupdatemode?branch=dev)
##### [SetViewportOptions method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setviewportoptions?branch=dev)
##### [SetViewportRect method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setviewportrect?branch=dev)
##### [SetViewportTransform method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-setviewporttransform?branch=dev)
##### [Stop method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-stop?branch=dev)
##### [SyncDisplayTransform method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-syncdisplaytransform?branch=dev)
##### [ZoomToRect Method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport-zoomtorect?branch=dev)
#### [IDirectManipulationViewport2](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationviewport2?branch=dev)
##### [AddBehavior method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport2-addbehavior?branch=dev)
##### [RemoveBehavior method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport2-removebehavior?branch=dev)
##### [RemoveAllBehaviors method](/windows/win32/content/DirectManipulation/nf-directmanipulation-idirectmanipulationviewport2-removeallbehaviors?branch=dev)
#### [IDirectManipulationViewportEventHandler](/windows/win32/content/DirectManipulation/nn-directmanipulation-idirectmanipulationviewporteventhandler?branch=dev)
##### [OnContentUpdated Method](/windows/win32/content/directmanipulation/nf-directmanipulation-idirectmanipulationviewporteventhandler-oncontentupdated?branch=dev)
##### [OnViewportStatusChanged Method](/windows/win32/content/directmanipulation/nf-directmanipulation-idirectmanipulationviewporteventhandler-onviewportstatuschanged?branch=dev)
##### [OnViewportUpdated Method](/windows/win32/content/directmanipulation/nf-directmanipulation-idirectmanipulationviewporteventhandler-onviewportupdated?branch=dev)
