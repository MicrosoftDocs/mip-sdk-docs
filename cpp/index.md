# MIP SDK for C++ Reference

The Microsoft Information Protection (MIP) SDK for C++ allows developers to manage and apply data protection policies to data and other digital assets. For guidance on how to use it, see [Microsoft Information Protection SDK documentation](https://learn.microsoft.com/information-protection/develop/).

The MIP SDK for C++ reference includes the following [classes](annotated.html):

| Class Name | Description |
|------------|-------------|
| [AccessDeniedError](classmip_1_1AccessDeniedError.html) | The user could not get access to the content |
| [Action](classmip_1_1Action.html) | Interface for an action |
| [AddContentFooterAction](classmip_1_1AddContentFooterAction.html) | An action class that specifies adding a content footer to the document |
| [AddContentHeaderAction](classmip_1_1AddContentHeaderAction.html) | An action class that specifies adding content header |
| [AddWatermarkAction](classmip_1_1AddWatermarkAction.html) | An action class that specifies adding watermark |
| [AdhocProtectionRequiredError](classmip_1_1AdhocProtectionRequiredError.html) | Adhoc protection should be set to complete the action on the file |
| [ApplicationInfo](structmip_1_1ApplicationInfo.html) | A struct that includes application-specific information |
| [ApplyLabelAction](classmip_1_1ApplyLabelAction.html) | Apply label actions require the calling application to apply a specific label |
| [AsyncControl](classmip_1_1AsyncControl.html) | Class used to cancel async operation |
| [AuthDelegate](classmip_1_1AuthDelegate.html) | Delegate for auth-related operations |
| [OAuth2Challenge](classmip_1_1AuthDelegate_1_1OAuth2Challenge.html) | Class that contains all the information required from the calling application in order to generate an OAuth2 token |
| [OAuth2Token](classmip_1_1AuthDelegate_1_1OAuth2Token.html) | A class containing access token info provided by an application |
| [BadInputError](classmip_1_1BadInputError.html) | Bad input error, thrown when the input to an SDK API is invalid |
| [ClassificationRequest](classmip_1_1ClassificationRequest.html) | Class that contains the request of a classification call on the Execution State |
| [ClassificationResult](classmip_1_1ClassificationResult.html) | Class that contains the result of a classification call on the Execution State |
| [ConsentDelegate](classmip_1_1ConsentDelegate.html) | Delegate for consent-related operations |
| [ConsentDeniedError](classmip_1_1ConsentDeniedError.html) | An operation that required consent from user was not granted consent |
| [ContentLabel](classmip_1_1ContentLabel.html) | Abstraction for a Microsoft Information Protection label that is applied to a piece of content, typically a document |
| [CustomAction](classmip_1_1CustomAction.html) | CustomAction is a generic action class that captures all the sub-properties of the action as a property bag |
| [DeprecatedApiError](classmip_1_1DeprecatedApiError.html) | Caller invoked a deprecated API |
| [Error](classmip_1_1Error.html) | Base class for all errors that will be reported (thrown or returned) from MIP SDK |
| [ExecutionState](classmip_1_1ExecutionState.html) | Interface for all the state needed to execute the engine |
| [FileEngine](classmip_1_1FileEngine.html) | This class provides an interface for all engine functions |
| [FileHandler](classmip_1_1FileHandler.html) | Interface for all file handling functions |
| [FileIOError](classmip_1_1FileIOError.html) | File IO error |
| [FileInspector](classmip_1_1FileInspector.html) |  |
| [FileProfile](classmip_1_1FileProfile.html) | FileProfile class is the root class for using the Microsoft Information Protection operations |
| [HttpDelegate](classmip_1_1HttpDelegate.html) | Interface for overriding HTTP handling |
| [HttpOperation](classmip_1_1HttpOperation.html) | Interface that describes a single HTTP operation, implemented by client app when overriding HttpDelegate |
| [HttpRequest](classmip_1_1HttpRequest.html) | Interface that describes a single HTTP request |
| [HttpResponse](classmip_1_1HttpResponse.html) | Interface that describes a single HTTP response, implemented by client app when overriding HttpDelegate |
| [Identity](classmip_1_1Identity.html) | Abstraction for identity |
| [InsufficientBufferError](classmip_1_1InsufficientBufferError.html) | Insufficient buffer error |
| [InternalError](classmip_1_1InternalError.html) | Internal error |
| [JustificationRequiredError](classmip_1_1JustificationRequiredError.html) |  |
| [JustifyAction](classmip_1_1JustifyAction.html) | Justify Action requires providing a justification to a label downgrade and setting the response in the execution state |
| [Label](classmip_1_1Label.html) | Abstraction for a single Microsoft Information Protection label |
| [LabelDisabledError](classmip_1_1LabelDisabledError.html) | Label is disabled or inactive |
| [LabelingOptions](classmip_1_1LabelingOptions.html) | Interface for configuring labeling options for the SetLabel/DeleteLabel methods |
| [LabelNotFoundError](classmip_1_1LabelNotFoundError.html) | Label ID is not recognized |
| [LoggerDelegate](classmip_1_1LoggerDelegate.html) | A class that defines the interface to the MIP SDK logger |
| [MetadataAction](classmip_1_1MetadataAction.html) | An Action that adds metadata information to the content |
| [MipContext](classmip_1_1MipContext.html) | MipContext represents state that is shared across all profiles, engines, handlers |
| [MsgAttachmentData](classmip_1_1MsgAttachmentData.html) |  |
| [MsgInspector](classmip_1_1MsgInspector.html) |  |
| [NetworkError](classmip_1_1NetworkError.html) | Networking error |
| [NoAuthTokenError](classmip_1_1NoAuthTokenError.html) | The user could not get access to the content due to missing authentication token |
| [NoPermissionsError](classmip_1_1NoPermissionsError.html) | The user could not get access to the content |
| [NoPolicyError](classmip_1_1NoPolicyError.html) | Tenant policy is not configured for classification/labels |
| [NotSupportedError](classmip_1_1NotSupportedError.html) | The operation requested by the application is not supported by the SDK |
| [OperationCancelledError](classmip_1_1OperationCancelledError.html) | Operation was cancelled |
| [PolicyEngine](classmip_1_1PolicyEngine.html) | This class provides an interface for all engine functions |
| [PolicyHandler](classmip_1_1PolicyHandler.html) | This class provides an interface for all policy handler functions on a file |
| [PolicyProfile](classmip_1_1PolicyProfile.html) | PolicyProfile class is the root class for using the Microsoft Information Protection operations |
| [PrivilegedRequiredError](classmip_1_1PrivilegedRequiredError.html) | Current label was assigned as a privileged operation (The equivalent to an administrator operation), therefore it can't be overridden |
| [ProtectAdhocAction](classmip_1_1ProtectAdhocAction.html) | An action class that specifies adding adhoc protection to the document |
| [ProtectAdhocDkAction](classmip_1_1ProtectAdhocDkAction.html) | An action class that specifies adding adhoc double key protection to the document |
| [ProtectByTemplateAction](classmip_1_1ProtectByTemplateAction.html) | An action class that specifies adding protection by template to the document |
| [ProtectByTemplateDkAction](classmip_1_1ProtectByTemplateDkAction.html) | An action class that specifies adding protection by template double key to the document |
| [ProtectDoNotForwardAction](classmip_1_1ProtectDoNotForwardAction.html) | An action class that specifies adding do not forward protection to the document |
| [ProtectDoNotForwardDkAction](classmip_1_1ProtectDoNotForwardDkAction.html) | An action class that specifies adding do not forward double key protection to the document |
| [ProtectionDescriptor](classmip_1_1ProtectionDescriptor.html) | Description of protection associated with a piece of content |
| [ProtectionDescriptorBuilder](classmip_1_1ProtectionDescriptorBuilder.html) | Constructs a ProtectionDescriptor that describes protection associated with a piece of content |
| [ProtectionEngine](classmip_1_1ProtectionEngine.html) | Manages protection-related actions related to a specific identity |
| [ProtectionHandler](classmip_1_1ProtectionHandler.html) | Manages protection-related actions for a specific protection configuration |
| [ProtectionProfile](classmip_1_1ProtectionProfile.html) | ProtectionProfile is the root class for performing protection operations |
| [ProtectionSettings](classmip_1_1ProtectionSettings.html) | Interface for configuring protection options for the SetLabel method |
| [ProxyAuthenticationError](classmip_1_1ProxyAuthenticationError.html) | Proxy authentication failure |
| [PublishingLicenseInfo](classmip_1_1PublishingLicenseInfo.html) | Holds the details of a Publishing License used to create a protection handler |
| [RecommendLabelAction](classmip_1_1RecommendLabelAction.html) | Recommend label actions are meant to suggest a label to the users |
| [RemoveContentFooterAction](classmip_1_1RemoveContentFooterAction.html) | An action class that specifies removing the content footer from the document |
| [RemoveContentHeaderAction](classmip_1_1RemoveContentHeaderAction.html) | An action class that specifies removing the content header from the document |
| [RemoveProtectionAction](classmip_1_1RemoveProtectionAction.html) | An action class that specifies removing protection from the document |
| [RemoveWatermarkAction](classmip_1_1RemoveWatermarkAction.html) | An action class that specifies removing the watermarking from the document |
| [SensitivityTypesRulePackage](classmip_1_1SensitivityTypesRulePackage.html) |  |
| [ServiceDisabledError](classmip_1_1ServiceDisabledError.html) | The user could not get access to the content due to a service being disabled |
| [Stream](classmip_1_1Stream.html) | A class that defines the interface between the MIP SDK and stream-based content |
| [TaskDispatcherDelegate](classmip_1_1TaskDispatcherDelegate.html) | A class that defines the interface to the MIP SDK task dispatcher |
| [TelemetryConfiguration](structmip_1_1TelemetryConfiguration.html) | Custom telemetry settings (not commonly used) |
| [TemplateDescriptor](classmip_1_1TemplateDescriptor.html) |  |
| [TemplateNotFoundError](classmip_1_1TemplateNotFoundError.html) | Template ID is not recognized by RMS service |
| [UserRights](classmip_1_1UserRights.html) | A group of users and the rights associated with them |
| [UserRoles](classmip_1_1UserRoles.html) | A group of users and the roles associated with them |
