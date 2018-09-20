
# <a name="item"></a><span data-ttu-id="23147-101">item</span><span class="sxs-lookup"><span data-stu-id="23147-101">item</span></span>

### <a name="officeofficemdcontextofficecontextmdmailboxofficecontextmailboxmditem"></a><span data-ttu-id="23147-102">[Office](office.md)[.context](office.context.md)[.mailbox](office.context.mailbox.md).item</span><span class="sxs-lookup"><span data-stu-id="23147-102">[Office](office.md)[.context](office.context.md)[.mailbox](office.context.mailbox.md).item</span></span>

<span data-ttu-id="23147-p101">Пространство имен `item` используется для доступа к выбранному в данный момент сообщению, приглашению на собрание или описанию встречи. Вы можете определить тип пространства имен `item` с помощью свойства [itemType](#itemtype-officemailboxenumsitemtypejavascriptapioutlook15officemailboxenumsitemtype).</span><span class="sxs-lookup"><span data-stu-id="23147-p101">The `item` namespace is used to access the currently selected message, meeting request, or appointment. You can determine the type of the `item` by using the [itemType](#itemtype-officemailboxenumsitemtypejavascriptapioutlook15officemailboxenumsitemtype) property.</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-105">Requirements</span><span class="sxs-lookup"><span data-stu-id="23147-105">Requirements</span></span>

|<span data-ttu-id="23147-106">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-106">Requirement</span></span>| <span data-ttu-id="23147-107">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-108">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-109">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-109">1.0</span></span>|
|[<span data-ttu-id="23147-110">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-111">Restricted</span><span class="sxs-lookup"><span data-stu-id="23147-111">Restricted</span></span>|
|[<span data-ttu-id="23147-112">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-113">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="23147-114">Элементы и методы</span><span class="sxs-lookup"><span data-stu-id="23147-114">Members and methods</span></span>

| <span data-ttu-id="23147-115">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-115">Member</span></span> | <span data-ttu-id="23147-116">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="23147-117">attachments</span><span class="sxs-lookup"><span data-stu-id="23147-117">attachments</span></span>](#attachments-arrayattachmentdetailsjavascriptapioutlook15officeattachmentdetails) | <span data-ttu-id="23147-118">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-118">Member</span></span> |
| [<span data-ttu-id="23147-119">bcc</span><span class="sxs-lookup"><span data-stu-id="23147-119">bcc</span></span>](#bcc-recipientsjavascriptapioutlook15officerecipients) | <span data-ttu-id="23147-120">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-120">Member</span></span> |
| [<span data-ttu-id="23147-121">body</span><span class="sxs-lookup"><span data-stu-id="23147-121">body</span></span>](#body-bodyjavascriptapioutlook15officebody) | <span data-ttu-id="23147-122">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-122">Member</span></span> |
| [<span data-ttu-id="23147-123">cc</span><span class="sxs-lookup"><span data-stu-id="23147-123">cc</span></span>](#cc-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients) | <span data-ttu-id="23147-124">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-124">Member</span></span> |
| [<span data-ttu-id="23147-125">conversationId</span><span class="sxs-lookup"><span data-stu-id="23147-125">conversationId</span></span>](#nullable-conversationid-string) | <span data-ttu-id="23147-126">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-126">Member</span></span> |
| [<span data-ttu-id="23147-127">dateTimeCreated</span><span class="sxs-lookup"><span data-stu-id="23147-127">dateTimeCreated</span></span>](#datetimecreated-date) | <span data-ttu-id="23147-128">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-128">Member</span></span> |
| [<span data-ttu-id="23147-129">dateTimeModified</span><span class="sxs-lookup"><span data-stu-id="23147-129">dateTimeModified</span></span>](#datetimemodified-date) | <span data-ttu-id="23147-130">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-130">Member</span></span> |
| [<span data-ttu-id="23147-131">end</span><span class="sxs-lookup"><span data-stu-id="23147-131">end</span></span>](#end-datetimejavascriptapioutlook15officetime) | <span data-ttu-id="23147-132">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-132">Member</span></span> |
| [<span data-ttu-id="23147-133">from</span><span class="sxs-lookup"><span data-stu-id="23147-133">from</span></span>](#from-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) | <span data-ttu-id="23147-134">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-134">Member</span></span> |
| [<span data-ttu-id="23147-135">internetMessageId</span><span class="sxs-lookup"><span data-stu-id="23147-135">internetMessageId</span></span>](#internetmessageid-string) | <span data-ttu-id="23147-136">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-136">Member</span></span> |
| [<span data-ttu-id="23147-137">itemClass</span><span class="sxs-lookup"><span data-stu-id="23147-137">itemClass</span></span>](#itemclass-string) | <span data-ttu-id="23147-138">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-138">Member</span></span> |
| [<span data-ttu-id="23147-139">itemId</span><span class="sxs-lookup"><span data-stu-id="23147-139">itemId</span></span>](#nullable-itemid-string) | <span data-ttu-id="23147-140">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-140">Member</span></span> |
| [<span data-ttu-id="23147-141">itemType</span><span class="sxs-lookup"><span data-stu-id="23147-141">itemType</span></span>](#itemtype-officemailboxenumsitemtypejavascriptapioutlook15officemailboxenumsitemtype) | <span data-ttu-id="23147-142">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-142">Member</span></span> |
| [<span data-ttu-id="23147-143">location</span><span class="sxs-lookup"><span data-stu-id="23147-143">location</span></span>](#location-stringlocationjavascriptapioutlook15officelocation) | <span data-ttu-id="23147-144">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-144">Member</span></span> |
| [<span data-ttu-id="23147-145">normalizedSubject</span><span class="sxs-lookup"><span data-stu-id="23147-145">normalizedSubject</span></span>](#normalizedsubject-string) | <span data-ttu-id="23147-146">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-146">Member</span></span> |
| [<span data-ttu-id="23147-147">notificationMessages</span><span class="sxs-lookup"><span data-stu-id="23147-147">notificationMessages</span></span>](#notificationmessages-notificationmessagesjavascriptapioutlook15officenotificationmessages) | <span data-ttu-id="23147-148">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-148">Member</span></span> |
| [<span data-ttu-id="23147-149">optionalAttendees</span><span class="sxs-lookup"><span data-stu-id="23147-149">optionalAttendees</span></span>](#optionalattendees-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients) | <span data-ttu-id="23147-150">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-150">Member</span></span> |
| [<span data-ttu-id="23147-151">organizer</span><span class="sxs-lookup"><span data-stu-id="23147-151">organizer</span></span>](#organizer-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) | <span data-ttu-id="23147-152">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-152">Member</span></span> |
| [<span data-ttu-id="23147-153">requiredAttendees</span><span class="sxs-lookup"><span data-stu-id="23147-153">requiredAttendees</span></span>](#requiredattendees-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients) | <span data-ttu-id="23147-154">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-154">Member</span></span> |
| [<span data-ttu-id="23147-155">sender</span><span class="sxs-lookup"><span data-stu-id="23147-155">sender</span></span>](#sender-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) | <span data-ttu-id="23147-156">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-156">Member</span></span> |
| [<span data-ttu-id="23147-157">start</span><span class="sxs-lookup"><span data-stu-id="23147-157">start</span></span>](#start-datetimejavascriptapioutlook15officetime) | <span data-ttu-id="23147-158">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-158">Member</span></span> |
| [<span data-ttu-id="23147-159">subject</span><span class="sxs-lookup"><span data-stu-id="23147-159">subject</span></span>](#subject-stringsubjectjavascriptapioutlook15officesubject) | <span data-ttu-id="23147-160">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-160">Member</span></span> |
| [<span data-ttu-id="23147-161">to</span><span class="sxs-lookup"><span data-stu-id="23147-161">to</span></span>](#to-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients) | <span data-ttu-id="23147-162">Элемент</span><span class="sxs-lookup"><span data-stu-id="23147-162">Member</span></span> |
| [<span data-ttu-id="23147-163">addFileAttachmentAsync</span><span class="sxs-lookup"><span data-stu-id="23147-163">addFileAttachmentAsync</span></span>](#addfileattachmentasyncuri-attachmentname-options-callback) | <span data-ttu-id="23147-164">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-164">Method</span></span> |
| [<span data-ttu-id="23147-165">addItemAttachmentAsync</span><span class="sxs-lookup"><span data-stu-id="23147-165">addItemAttachmentAsync</span></span>](#additemattachmentasyncitemid-attachmentname-options-callback) | <span data-ttu-id="23147-166">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-166">Method</span></span> |
| [<span data-ttu-id="23147-167">close</span><span class="sxs-lookup"><span data-stu-id="23147-167">close</span></span>](#close) | <span data-ttu-id="23147-168">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-168">Method</span></span> |
| [<span data-ttu-id="23147-169">displayReplyAllForm</span><span class="sxs-lookup"><span data-stu-id="23147-169">displayReplyAllForm</span></span>](#displayreplyallformformdata) | <span data-ttu-id="23147-170">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-170">Method</span></span> |
| [<span data-ttu-id="23147-171">displayReplyForm</span><span class="sxs-lookup"><span data-stu-id="23147-171">displayReplyForm</span></span>](#displayreplyformformdata) | <span data-ttu-id="23147-172">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-172">Method</span></span> |
| [<span data-ttu-id="23147-173">getEntities</span><span class="sxs-lookup"><span data-stu-id="23147-173">getEntities</span></span>](#getentities--entitiesjavascriptapioutlook15officeentities) | <span data-ttu-id="23147-174">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-174">Method</span></span> |
| [<span data-ttu-id="23147-175">getEntitiesByType</span><span class="sxs-lookup"><span data-stu-id="23147-175">getEntitiesByType</span></span>](#getentitiesbytypeentitytype--nullable-arraystringcontactjavascriptapioutlook15officecontactmeetingsuggestionjavascriptapioutlook15officemeetingsuggestionphonenumberjavascriptapioutlook15officephonenumbertasksuggestionjavascriptapioutlook15officetasksuggestion) | <span data-ttu-id="23147-176">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-176">Method</span></span> |
| [<span data-ttu-id="23147-177">getFilteredEntitiesByName</span><span class="sxs-lookup"><span data-stu-id="23147-177">getFilteredEntitiesByName</span></span>](#getfilteredentitiesbynamename--nullable-arraystringcontactjavascriptapioutlook15officecontactmeetingsuggestionjavascriptapioutlook15officemeetingsuggestionphonenumberjavascriptapioutlook15officephonenumbertasksuggestionjavascriptapioutlook15officetasksuggestion) | <span data-ttu-id="23147-178">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-178">Method</span></span> |
| [<span data-ttu-id="23147-179">getRegExMatches</span><span class="sxs-lookup"><span data-stu-id="23147-179">getRegExMatches</span></span>](#getregexmatches--object) | <span data-ttu-id="23147-180">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-180">Method</span></span> |
| [<span data-ttu-id="23147-181">getRegExMatchesByName</span><span class="sxs-lookup"><span data-stu-id="23147-181">getRegExMatchesByName</span></span>](#getregexmatchesbynamename--nullable-array-string-) | <span data-ttu-id="23147-182">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-182">Method</span></span> |
| [<span data-ttu-id="23147-183">getSelectedDataAsync</span><span class="sxs-lookup"><span data-stu-id="23147-183">getSelectedDataAsync</span></span>](#getselecteddataasynccoerciontype-options-callback--string) | <span data-ttu-id="23147-184">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-184">Method</span></span> |
| [<span data-ttu-id="23147-185">loadCustomPropertiesAsync</span><span class="sxs-lookup"><span data-stu-id="23147-185">loadCustomPropertiesAsync</span></span>](#loadcustompropertiesasynccallback-usercontext) | <span data-ttu-id="23147-186">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-186">Method</span></span> |
| [<span data-ttu-id="23147-187">removeAttachmentAsync</span><span class="sxs-lookup"><span data-stu-id="23147-187">removeAttachmentAsync</span></span>](#removeattachmentasyncattachmentid-options-callback) | <span data-ttu-id="23147-188">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-188">Method</span></span> |
| [<span data-ttu-id="23147-189">saveAsync</span><span class="sxs-lookup"><span data-stu-id="23147-189">saveAsync</span></span>](#saveasyncoptions-callback) | <span data-ttu-id="23147-190">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-190">Method</span></span> |
| [<span data-ttu-id="23147-191">setSelectedDataAsync</span><span class="sxs-lookup"><span data-stu-id="23147-191">setSelectedDataAsync</span></span>](#setselecteddataasyncdata-options-callback) | <span data-ttu-id="23147-192">Метод</span><span class="sxs-lookup"><span data-stu-id="23147-192">Method</span></span> |

### <a name="example"></a><span data-ttu-id="23147-193">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-193">Example</span></span>

<span data-ttu-id="23147-194">В примере кода JavaScript, приведенном ниже, показано, как получить доступ к свойству `subject` текущего элемента в Outlook.</span><span class="sxs-lookup"><span data-stu-id="23147-194">The following JavaScript code example shows how to access the `subject` property of the current item in Outlook.</span></span>

```
// The initialize function is required for all apps.
Office.initialize = function () {
    // Checks for the DOM to load using the jQuery ready function.
    $(document).ready(function () {
    // After the DOM is loaded, app-specific code can run.
    var item = Office.context.mailbox.item;
    var subject = item.subject;
    // Continue with processing the subject of the current item,
    // which can be a message or appointment.
    });
}
```

### <a name="members"></a><span data-ttu-id="23147-195">Элементы</span><span class="sxs-lookup"><span data-stu-id="23147-195">Members</span></span>

#### <a name="attachments-arrayattachmentdetailsjavascriptapioutlook15officeattachmentdetails"></a><span data-ttu-id="23147-196">attachments :Array.<[AttachmentDetails](/javascript/api/outlook_1_5/office.attachmentdetails)></span><span class="sxs-lookup"><span data-stu-id="23147-196">attachments :Array.<[AttachmentDetails](/javascript/api/outlook_1_5/office.attachmentdetails)></span></span>

<span data-ttu-id="23147-p102">Получает массив вложений для элемента. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p102">Gets an array of attachments for the item. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-199">Определенные типы файлов блокируемых в Outlook из-за потенциальных проблем безопасности и поэтому не возвращаются.</span><span class="sxs-lookup"><span data-stu-id="23147-199">Certain types of files are blocked by Outlook due to potential security issues and are therefore not returned.</span></span> <span data-ttu-id="23147-200">Для получения дополнительных сведений см [Блокировка вложений в Outlook](https://support.office.com/article/Blocked-attachments-in-Outlook-434752E1-02D3-4E90-9124-8B81E49A8519).</span><span class="sxs-lookup"><span data-stu-id="23147-200">For more information, see [Blocked attachments in Outlook](https://support.office.com/article/Blocked-attachments-in-Outlook-434752E1-02D3-4E90-9124-8B81E49A8519).</span></span>

##### <a name="type"></a><span data-ttu-id="23147-201">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-201">Type:</span></span>

*   <span data-ttu-id="23147-202">Array.<[AttachmentDetails](/javascript/api/outlook_1_5/office.attachmentdetails)></span><span class="sxs-lookup"><span data-stu-id="23147-202">Array.<[AttachmentDetails](/javascript/api/outlook_1_5/office.attachmentdetails)></span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-203">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-203">Requirements</span></span>

|<span data-ttu-id="23147-204">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-204">Requirement</span></span>| <span data-ttu-id="23147-205">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-205">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-206">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-206">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-207">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-207">1.0</span></span>|
|[<span data-ttu-id="23147-208">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-208">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-209">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-209">ReadItem</span></span>|
|[<span data-ttu-id="23147-210">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-210">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-211">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-211">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-212">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-212">Example</span></span>

<span data-ttu-id="23147-213">С помощью приведенного ниже кода можно создать HTML-строку с подробными сведениями обо всех вложениях для текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-213">The following code builds an HTML string with details of all attachments on the current item.</span></span>

```
var _Item = Office.context.mailbox.item;
var outputString = "";

if (_Item.attachments.length > 0) {
  for (i = 0 ; i < _Item.attachments.length ; i++) {
    var _att = _Item.attachments[i];
    outputString += "<BR>" + i + ". Name: ";
    outputString += _att.name;
    outputString += "<BR>ID: " + _att.id;
    outputString += "<BR>contentType: " + _att.contentType;
    outputString += "<BR>size: " + _att.size;
    outputString += "<BR>attachmentType: " + _att.attachmentType;
    outputString += "<BR>isInline: " + _att.isInline;
  }
}

// Do something with outputString
```

####  <a name="bcc-recipientsjavascriptapioutlook15officerecipients"></a><span data-ttu-id="23147-214">bcc :[Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-214">bcc :[Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

<span data-ttu-id="23147-215">Получает объект, который предоставляет методы для получения или обновления получателей в строке (Скрытая копия) скрытой копии сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-215">Gets an object that provides methods to get or update the recipients on the Bcc (blind carbon copy) line of a message.</span></span> <span data-ttu-id="23147-216">Только в режиме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-216">Compose mode only.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-217">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-217">Type:</span></span>

*   [<span data-ttu-id="23147-218">Recipients</span><span class="sxs-lookup"><span data-stu-id="23147-218">Recipients</span></span>](/javascript/api/outlook_1_5/office.recipients)

##### <a name="requirements"></a><span data-ttu-id="23147-219">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-219">Requirements</span></span>

|<span data-ttu-id="23147-220">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-220">Requirement</span></span>| <span data-ttu-id="23147-221">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-221">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-222">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-222">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-223">1.1</span><span class="sxs-lookup"><span data-stu-id="23147-223">1.1</span></span>|
|[<span data-ttu-id="23147-224">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-224">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-225">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-225">ReadItem</span></span>|
|[<span data-ttu-id="23147-226">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-226">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-227">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-227">Compose</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-228">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-228">Example</span></span>

```
Office.context.mailbox.item.bcc.setAsync( ['alice@contoso.com', 'bob@contoso.com'] );
Office.context.mailbox.item.bcc.addAsync( ['jason@contoso.com'] );
Office.context.mailbox.item.bcc.getAsync(callback);

function callback(asyncResult) {
  var arrayOfBccRecipients = asyncResult.value;
}
```

####  <a name="body-bodyjavascriptapioutlook15officebody"></a><span data-ttu-id="23147-229">body :[Body](/javascript/api/outlook_1_5/office.body)</span><span class="sxs-lookup"><span data-stu-id="23147-229">body :[Body](/javascript/api/outlook_1_5/office.body)</span></span>

<span data-ttu-id="23147-230">Получает объект, предоставляющий методы для работы с основным текстом элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-230">Gets an object that provides methods for manipulating the body of an item.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-231">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-231">Type:</span></span>

*   [<span data-ttu-id="23147-232">Body</span><span class="sxs-lookup"><span data-stu-id="23147-232">Body</span></span>](/javascript/api/outlook_1_5/office.body)

##### <a name="requirements"></a><span data-ttu-id="23147-233">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-233">Requirements</span></span>

|<span data-ttu-id="23147-234">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-234">Requirement</span></span>| <span data-ttu-id="23147-235">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-235">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-236">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-236">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-237">1.1</span><span class="sxs-lookup"><span data-stu-id="23147-237">1.1</span></span>|
|[<span data-ttu-id="23147-238">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-238">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-239">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-239">ReadItem</span></span>|
|[<span data-ttu-id="23147-240">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-240">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-241">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-241">Compose or read</span></span>|

####  <a name="cc-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients"></a><span data-ttu-id="23147-242">cc: массив. <[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[получателей](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-242">cc :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

<span data-ttu-id="23147-243">Предоставляет доступ к «копия» (копия) получателей сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-243">Provides access to the Cc (carbon copy) recipients of a message.</span></span> <span data-ttu-id="23147-244">Уровень доступа и тип объекта, зависит от режима текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-244">The type of object and level of access depends on the mode of the current item.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-245">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-245">Read mode</span></span>

<span data-ttu-id="23147-p106">Свойство `cc` возвращает массив, который содержит объект `EmailAddressDetails` для каждого получателя, указанного в строке **Копия** сообщения. Коллекция может включать не более 100 элементов.</span><span class="sxs-lookup"><span data-stu-id="23147-p106">The `cc` property returns an array that contains an `EmailAddressDetails` object for each recipient listed on the **Cc** line of the message. The collection is limited to a maximum of 100 members.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-248">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-248">Compose mode</span></span>

<span data-ttu-id="23147-249">`cc` Возвращает свойство `Recipients` объект, предоставляющий методы для получения или обновления получателей в строке **копия** сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-249">The `cc` property returns a `Recipients` object that provides methods to get or update the recipients on the **Cc** line of the message.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-250">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-250">Type:</span></span>

*   <span data-ttu-id="23147-251">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-251">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-252">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-252">Requirements</span></span>

|<span data-ttu-id="23147-253">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-253">Requirement</span></span>| <span data-ttu-id="23147-254">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-254">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-255">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-255">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-256">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-256">1.0</span></span>|
|[<span data-ttu-id="23147-257">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-257">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-258">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-258">ReadItem</span></span>|
|[<span data-ttu-id="23147-259">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-259">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-260">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-260">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-261">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-261">Example</span></span>

```
Office.context.mailbox.item.cc.setAsync( ['alice@contoso.com', 'bob@contoso.com'] );
Office.context.mailbox.item.cc.addAsync( ['jason@contoso.com'] );
Office.context.mailbox.item.cc.getAsync(callback);

function callback(asyncResult) {
  var arrayOfCcRecipients = asyncResult.value;
}
```

####  <a name="nullable-conversationid-string"></a><span data-ttu-id="23147-262">(nullable) conversationId :String</span><span class="sxs-lookup"><span data-stu-id="23147-262">(nullable) conversationId :String</span></span>

<span data-ttu-id="23147-263">Получает идентификатор разговора по электронной почте, содержащего конкретное сообщение.</span><span class="sxs-lookup"><span data-stu-id="23147-263">Gets an identifier for the email conversation that contains a particular message.</span></span>

<span data-ttu-id="23147-p107">Вы можете получить целочисленное значение этого свойства, если ваше почтовое приложение активируется в формах просмотра или формах создания ответов. Если пользователь изменит тему ответа, после его отправки идентификатор беседы будет изменен, и полученное ранее значение будет недействительным.</span><span class="sxs-lookup"><span data-stu-id="23147-p107">You can get an integer for this property if your mail app is activated in read forms or responses in compose forms. If subsequently the user changes the subject of the reply message, upon sending the reply, the conversation ID for that message will change and that value you obtained earlier will no longer apply.</span></span>

<span data-ttu-id="23147-p108">Это свойство имеет значение NULL для нового элемента в форме создания. Свойство `conversationId` вернет значение, если пользователь задаст тему и сохранит элемент.</span><span class="sxs-lookup"><span data-stu-id="23147-p108">You get null for this property for a new item in a compose form. If the user sets a subject and saves the item, the `conversationId` property will return a value.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-268">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-268">Type:</span></span>

*   <span data-ttu-id="23147-269">String</span><span class="sxs-lookup"><span data-stu-id="23147-269">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-270">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-270">Requirements</span></span>

|<span data-ttu-id="23147-271">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-271">Requirement</span></span>| <span data-ttu-id="23147-272">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-272">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-273">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-273">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-274">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-274">1.0</span></span>|
|[<span data-ttu-id="23147-275">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-275">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-276">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-276">ReadItem</span></span>|
|[<span data-ttu-id="23147-277">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-277">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-278">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-278">Compose or read</span></span>|

#### <a name="datetimecreated-date"></a><span data-ttu-id="23147-279">dateTimeCreated :Date</span><span class="sxs-lookup"><span data-stu-id="23147-279">dateTimeCreated :Date</span></span>

<span data-ttu-id="23147-p109">Получает дату и время создания элемента. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p109">Gets the date and time that an item was created. Read mode only.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-282">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-282">Type:</span></span>

*   <span data-ttu-id="23147-283">Date</span><span class="sxs-lookup"><span data-stu-id="23147-283">Date</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-284">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-284">Requirements</span></span>

|<span data-ttu-id="23147-285">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-285">Requirement</span></span>| <span data-ttu-id="23147-286">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-286">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-287">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-287">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-288">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-288">1.0</span></span>|
|[<span data-ttu-id="23147-289">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-289">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-290">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-290">ReadItem</span></span>|
|[<span data-ttu-id="23147-291">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-291">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-292">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-292">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-293">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-293">Example</span></span>

```
var created = Office.context.mailbox.item.dateTimeCreated;
```

#### <a name="datetimemodified-date"></a><span data-ttu-id="23147-294">dateTimeModified :Date</span><span class="sxs-lookup"><span data-stu-id="23147-294">dateTimeModified :Date</span></span>

<span data-ttu-id="23147-p110">Получает дату и время последнего изменения элемента. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p110">Gets the date and time that an item was last modified. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-297">Этот член не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-297">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-298">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-298">Type:</span></span>

*   <span data-ttu-id="23147-299">Date</span><span class="sxs-lookup"><span data-stu-id="23147-299">Date</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-300">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-300">Requirements</span></span>

|<span data-ttu-id="23147-301">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-301">Requirement</span></span>| <span data-ttu-id="23147-302">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-302">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-303">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-303">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-304">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-304">1.0</span></span>|
|[<span data-ttu-id="23147-305">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-305">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-306">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-306">ReadItem</span></span>|
|[<span data-ttu-id="23147-307">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-307">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-308">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-308">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-309">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-309">Example</span></span>

```
var modified = Office.context.mailbox.item.dateTimeModified;
```

####  <a name="end-datetimejavascriptapioutlook15officetime"></a><span data-ttu-id="23147-310">end :Date|[Time](/javascript/api/outlook_1_5/office.time)</span><span class="sxs-lookup"><span data-stu-id="23147-310">end :Date|[Time](/javascript/api/outlook_1_5/office.time)</span></span>

<span data-ttu-id="23147-311">Получает или задает дату и время окончания встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-311">Gets or sets the date and time that the appointment is to end.</span></span>

<span data-ttu-id="23147-p111">Свойство `end` представлено в виде значения даты и времени в формате UTC. Преобразовать значение свойства end в местные значения даты и времени клиента можно с помощью метода [`convertToLocalClientTime`](office.context.mailbox.md#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime).</span><span class="sxs-lookup"><span data-stu-id="23147-p111">The `end` property is expressed as a Coordinated Universal Time (UTC) date and time value. You can use the [`convertToLocalClientTime`](office.context.mailbox.md#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime) method to convert the end property value to the client’s local date and time.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-314">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-314">Read mode</span></span>

<span data-ttu-id="23147-315">Свойство `end` возвращает объект `Date`.</span><span class="sxs-lookup"><span data-stu-id="23147-315">The `end` property returns a `Date` object.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-316">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-316">Compose mode</span></span>

<span data-ttu-id="23147-317">Свойство `end` возвращает объект `Time`.</span><span class="sxs-lookup"><span data-stu-id="23147-317">The `end` property returns a `Time` object.</span></span>

<span data-ttu-id="23147-318">Если вы задаете время окончания с помощью метода [`Time.setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-), необходимо использовать метод [`convertToUtcClientTime`](office.context.mailbox.md#converttoutcclienttimeinput--date) для преобразования местного времени на клиенте в формат UTC для сервера.</span><span class="sxs-lookup"><span data-stu-id="23147-318">When you use the [`Time.setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) method to set the end time, you should use the [`convertToUtcClientTime`](office.context.mailbox.md#converttoutcclienttimeinput--date) method to convert the local time on the client to UTC for the server.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-319">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-319">Type:</span></span>

*   <span data-ttu-id="23147-320">Date | [Time](/javascript/api/outlook_1_5/office.time)</span><span class="sxs-lookup"><span data-stu-id="23147-320">Date | [Time](/javascript/api/outlook_1_5/office.time)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-321">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-321">Requirements</span></span>

|<span data-ttu-id="23147-322">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-322">Requirement</span></span>| <span data-ttu-id="23147-323">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-323">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-324">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-324">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-325">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-325">1.0</span></span>|
|[<span data-ttu-id="23147-326">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-326">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-327">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-327">ReadItem</span></span>|
|[<span data-ttu-id="23147-328">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-328">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-329">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-329">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-330">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-330">Example</span></span>

<span data-ttu-id="23147-331">В примере ниже показано, как с помощью метода [`setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) объекта `Time` задать время окончания встречи в режиме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-331">The following example sets the end time of an appointment in compose mode by using the [`setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) method of the `Time` object.</span></span>

```
var endTime = new Date("3/14/2015");
var options = {
  // Pass information that can be used
  // in the callback
     asyncContext: {verb:"Set"}
}
Office.context.mailbox.item.end.setAsync(endTime, options, function(result) {
  if (result.error) {
    console.debug(result.error);
  } else {
    // Access the asyncContext that was passed to the setAsync function
    console.debug("End Time " + result.asyncContext.verb);
  }
});
```

#### <a name="from-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails"></a><span data-ttu-id="23147-332">from :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span><span class="sxs-lookup"><span data-stu-id="23147-332">from :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span></span>

<span data-ttu-id="23147-p112">Получает электронный адрес отправителя сообщения. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p112">Gets the email address of the sender of a message. Read mode only.</span></span>

<span data-ttu-id="23147-p113">Свойства `from` и [`sender`](#sender-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) представляют одно лицо, если сообщение не отправлено представителем. В противном случае свойство `from` представляет лицо, делегировавшее полномочия, а свойство sender — представителя.</span><span class="sxs-lookup"><span data-stu-id="23147-p113">The `from` and [`sender`](#sender-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) properties represent the same person unless the message is sent by a delegate. In that case, the `from` property represents the delegator, and the sender property represents the delegate.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-337">`recipientType` Свойства `EmailAddressDetails` объект в `from` — это свойство `undefined`.</span><span class="sxs-lookup"><span data-stu-id="23147-337">The `recipientType` property of the `EmailAddressDetails` object in the `from` property is `undefined`.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-338">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-338">Type:</span></span>

*   [<span data-ttu-id="23147-339">EmailAddressDetails</span><span class="sxs-lookup"><span data-stu-id="23147-339">EmailAddressDetails</span></span>](/javascript/api/outlook_1_5/office.emailaddressdetails)

##### <a name="requirements"></a><span data-ttu-id="23147-340">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-340">Requirements</span></span>

|<span data-ttu-id="23147-341">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-341">Requirement</span></span>| <span data-ttu-id="23147-342">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-342">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-343">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-343">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-344">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-344">1.0</span></span>|
|[<span data-ttu-id="23147-345">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-345">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-346">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-346">ReadItem</span></span>|
|[<span data-ttu-id="23147-347">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-347">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-348">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-348">Read</span></span>|

#### <a name="internetmessageid-string"></a><span data-ttu-id="23147-349">internetMessageId :String</span><span class="sxs-lookup"><span data-stu-id="23147-349">internetMessageId :String</span></span>

<span data-ttu-id="23147-p114">Получает идентификатор интернет-сообщения для электронного сообщения. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p114">Gets the Internet message identifier for an email message. Read mode only.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-352">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-352">Type:</span></span>

*   <span data-ttu-id="23147-353">String</span><span class="sxs-lookup"><span data-stu-id="23147-353">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-354">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-354">Requirements</span></span>

|<span data-ttu-id="23147-355">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-355">Requirement</span></span>| <span data-ttu-id="23147-356">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-356">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-357">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-357">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-358">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-358">1.0</span></span>|
|[<span data-ttu-id="23147-359">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-359">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-360">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-360">ReadItem</span></span>|
|[<span data-ttu-id="23147-361">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-361">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-362">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-362">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-363">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-363">Example</span></span>

```
var internetMessageId = Office.context.mailbox.item.internetMessageId;
```

#### <a name="itemclass-string"></a><span data-ttu-id="23147-364">itemClass :String</span><span class="sxs-lookup"><span data-stu-id="23147-364">itemClass :String</span></span>

<span data-ttu-id="23147-p115">Получает класс элемента веб-служб Exchange для выбранного элемента. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p115">Gets the Exchange Web Services item class of the selected item. Read mode only.</span></span>

<span data-ttu-id="23147-p116">Свойство `itemClass` указывает класс сообщения выбранного элемента. Ниже приводятся классы сообщения по умолчанию для элемента сообщения или встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-p116">The `itemClass` property specifies the message class of the selected item. The following are the default message classes for the message or appointment item.</span></span>

| <span data-ttu-id="23147-369">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-369">Type</span></span> | <span data-ttu-id="23147-370">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-370">Description</span></span> | <span data-ttu-id="23147-371">Класс элемента</span><span class="sxs-lookup"><span data-stu-id="23147-371">item class</span></span> |
| --- | --- | --- |
| <span data-ttu-id="23147-372">Элементы встречи</span><span class="sxs-lookup"><span data-stu-id="23147-372">Appointment items</span></span> | <span data-ttu-id="23147-373">Это элементы календаря для класса элемента `IPM.Appointment` или `IPM.Appointment.Occurence`.</span><span class="sxs-lookup"><span data-stu-id="23147-373">These are calendar items of the item class `IPM.Appointment` or `IPM.Appointment.Occurence`.</span></span> | `IPM.Appointment`<br />`IPM.Appointment.Occurence` |
| <span data-ttu-id="23147-374">Элементы сообщения</span><span class="sxs-lookup"><span data-stu-id="23147-374">Message items</span></span> | <span data-ttu-id="23147-375">Сюда входят электронные сообщения, для которых по умолчанию задан класс сообщения `IPM.Note`, а также приглашения на собрания, ответы на них и уведомления об их отмене, использующие `IPM.Schedule.Meeting` в качестве базового класса сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-375">These include email messages that have the default message class `IPM.Note`, and meeting requests, responses, and cancellations, that use `IPM.Schedule.Meeting` as the base message class.</span></span> | `IPM.Note`<br />`IPM.Schedule.Meeting.Request`<br />`IPM.Schedule.Meeting.Neg`<br />`IPM.Schedule.Meeting.Pos`<br />`IPM.Schedule.Meeting.Tent`<br />`IPM.Schedule.Meeting.Canceled` |

<span data-ttu-id="23147-376">Можно создавать настраиваемые классы сообщения, расширяющие классы сообщения по умолчанию, например настраиваемый класс сообщения о встрече `IPM.Appointment.Contoso`.</span><span class="sxs-lookup"><span data-stu-id="23147-376">You can create custom message classes that extends a default message class, for example, a custom appointment message class `IPM.Appointment.Contoso`.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-377">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-377">Type:</span></span>

*   <span data-ttu-id="23147-378">String</span><span class="sxs-lookup"><span data-stu-id="23147-378">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-379">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-379">Requirements</span></span>

|<span data-ttu-id="23147-380">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-380">Requirement</span></span>| <span data-ttu-id="23147-381">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-381">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-382">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-382">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-383">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-383">1.0</span></span>|
|[<span data-ttu-id="23147-384">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-384">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-385">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-385">ReadItem</span></span>|
|[<span data-ttu-id="23147-386">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-386">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-387">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-387">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-388">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-388">Example</span></span>

```
var itemClass = Office.context.mailbox.item.itemClass;
```

#### <a name="nullable-itemid-string"></a><span data-ttu-id="23147-389">(nullable) itemId :String</span><span class="sxs-lookup"><span data-stu-id="23147-389">(nullable) itemId :String</span></span>

<span data-ttu-id="23147-p117">Получает идентификатор элемента веб-служб Exchange для текущего элемента. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p117">Gets the Exchange Web Services item identifier for the current item. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-392">Идентификатор, возвращаемый свойством `itemId`, совпадает с идентификатором элемента веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="23147-392">The identifier returned by the `itemId` property is the same as the Exchange Web Services item identifier.</span></span> <span data-ttu-id="23147-393">`itemId` Свойство не совпадать с Идентификатором, используемым API-Интерфейс REST Outlook или идентификатор записи Outlook.</span><span class="sxs-lookup"><span data-stu-id="23147-393">The `itemId` property is not identical to the Outlook Entry ID or the ID used by the Outlook REST API.</span></span> <span data-ttu-id="23147-394">Прежде чем вносить API-Интерфейс REST для звонков с помощью этого значения, его следует преобразовать с помощью [Office.context.mailbox.convertToRestId](office.context.mailbox.md#converttorestiditemid-restversion--string).</span><span class="sxs-lookup"><span data-stu-id="23147-394">Before making REST API calls using this value, it should be converted using [Office.context.mailbox.convertToRestId](office.context.mailbox.md#converttorestiditemid-restversion--string).</span></span> <span data-ttu-id="23147-395">Для получения дополнительных сведений показано [Использование API REST Outlook из надстройки Outlook](https://docs.microsoft.com/outlook/add-ins/use-rest-api#get-the-item-id).</span><span class="sxs-lookup"><span data-stu-id="23147-395">For more details, see [Use the Outlook REST APIs from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/use-rest-api#get-the-item-id).</span></span>

<span data-ttu-id="23147-p119">Свойство `itemId` недоступно в режиме создания. Если требуется идентификатор элемента, с помощью метода [`saveAsync`](#saveasyncoptions-callback) можно сохранить элемент в хранилище. При этом в параметре [`AsyncResult.value`](/javascript/api/office/office.asyncresult) функции обратного вызова возвращается идентификатор элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-p119">The `itemId` property is not available in compose mode. If an item identifier is required, the [`saveAsync`](#saveasyncoptions-callback) method can be used to save the item to the store, which will return the item identifier in the [`AsyncResult.value`](/javascript/api/office/office.asyncresult) parameter in the callback function.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-398">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-398">Type:</span></span>

*   <span data-ttu-id="23147-399">String</span><span class="sxs-lookup"><span data-stu-id="23147-399">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-400">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-400">Requirements</span></span>

|<span data-ttu-id="23147-401">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-401">Requirement</span></span>| <span data-ttu-id="23147-402">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-402">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-403">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-403">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-404">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-404">1.0</span></span>|
|[<span data-ttu-id="23147-405">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-405">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-406">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-406">ReadItem</span></span>|
|[<span data-ttu-id="23147-407">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-407">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-408">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-408">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-409">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-409">Example</span></span>

<span data-ttu-id="23147-p120">Указанный ниже код проверяет наличие идентификатора элемента. Если свойство `itemId` возвращает значение `null` или `undefined`, элемент будет сохранен в хранилище, а из асинхронного результата будет получен идентификатор элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-p120">The following code checks for the presence of an item identifier. If the `itemId` property returns `null` or `undefined`, it saves the item to the store and gets the item identifier from the asynchronous result.</span></span>

```
var itemId = Office.context.mailbox.item.itemId;
if (itemId === null || itemId == undefined) {
  Office.context.mailbox.item.saveAsync(function(result){
    itemId = result.value;
  });
}
```

####  <a name="itemtype-officemailboxenumsitemtypejavascriptapioutlook15officemailboxenumsitemtype"></a><span data-ttu-id="23147-412">itemType :[Office.MailboxEnums.ItemType](/javascript/api/outlook_1_5/office.mailboxenums.itemtype)</span><span class="sxs-lookup"><span data-stu-id="23147-412">itemType :[Office.MailboxEnums.ItemType](/javascript/api/outlook_1_5/office.mailboxenums.itemtype)</span></span>

<span data-ttu-id="23147-413">Получает тип элемента, который представляет экземпляр.</span><span class="sxs-lookup"><span data-stu-id="23147-413">Gets the type of item that an instance represents.</span></span>

<span data-ttu-id="23147-414">Свойство `itemType` возвращает одно из значений перечисления `ItemType`, которое указывает, является ли экземпляр объекта `item` сообщением или встречей.</span><span class="sxs-lookup"><span data-stu-id="23147-414">The `itemType` property returns one of the `ItemType` enumeration values, indicating whether the `item` object instance is a message or an appointment.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-415">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-415">Type:</span></span>

*   [<span data-ttu-id="23147-416">Office.MailboxEnums.ItemType</span><span class="sxs-lookup"><span data-stu-id="23147-416">Office.MailboxEnums.ItemType</span></span>](/javascript/api/outlook_1_5/office.mailboxenums.itemtype)

##### <a name="requirements"></a><span data-ttu-id="23147-417">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-417">Requirements</span></span>

|<span data-ttu-id="23147-418">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-418">Requirement</span></span>| <span data-ttu-id="23147-419">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-419">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-420">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-420">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-421">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-421">1.0</span></span>|
|[<span data-ttu-id="23147-422">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-422">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-423">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-423">ReadItem</span></span>|
|[<span data-ttu-id="23147-424">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-424">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-425">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-425">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-426">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-426">Example</span></span>

```
if (Office.context.mailbox.item.itemType == Office.MailboxEnums.ItemType.Message)
  // do something
else
  // do something else
```

####  <a name="location-stringlocationjavascriptapioutlook15officelocation"></a><span data-ttu-id="23147-427">location :String|[Location](/javascript/api/outlook_1_5/office.location)</span><span class="sxs-lookup"><span data-stu-id="23147-427">location :String|[Location](/javascript/api/outlook_1_5/office.location)</span></span>

<span data-ttu-id="23147-428">Получает или задает место встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-428">Gets or sets the location of an appointment.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-429">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-429">Read mode</span></span>

<span data-ttu-id="23147-430">Свойство `location` возвращает строку, содержащую сведения о месте встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-430">The `location` property returns a string that contains the location of the appointment.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-431">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-431">Compose mode</span></span>

<span data-ttu-id="23147-432">Свойство `location` возвращает объект `Location`, предоставляющий методы, которые используются для получения и задания места встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-432">The `location` property returns a `Location` object that provides methods that are used to get and set the location of the appointment.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-433">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-433">Type:</span></span>

*   <span data-ttu-id="23147-434">String | [Location](/javascript/api/outlook_1_5/office.location)</span><span class="sxs-lookup"><span data-stu-id="23147-434">String | [Location](/javascript/api/outlook_1_5/office.location)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-435">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-435">Requirements</span></span>

|<span data-ttu-id="23147-436">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-436">Requirement</span></span>| <span data-ttu-id="23147-437">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-437">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-438">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-438">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-439">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-439">1.0</span></span>|
|[<span data-ttu-id="23147-440">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-440">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-441">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-441">ReadItem</span></span>|
|[<span data-ttu-id="23147-442">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-442">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-443">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-443">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-444">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-444">Example</span></span>

```
var userContext = { value : 1 };
Office.context.mailbox.item.location.getAsync( { context: userContext}, callback);

function callback(asyncResult) {
  var context = asyncResult.context;
  var location = asyncResult.value;
}
```

#### <a name="normalizedsubject-string"></a><span data-ttu-id="23147-445">normalizedSubject :String</span><span class="sxs-lookup"><span data-stu-id="23147-445">normalizedSubject :String</span></span>

<span data-ttu-id="23147-p121">Получает тему элемента со всеми удаленными префиксами (включая `RE:` и `FWD:`). Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p121">Gets the subject of an item, with all prefixes removed (including `RE:` and `FWD:`). Read mode only.</span></span>

<span data-ttu-id="23147-p122">Свойство normalizedSubject получает тему элемента со стандартными префиксами (такими как `RE:` и `FW:`), добавляемыми почтовыми программами. Для получения темы элемента с неизмененными префиксами используйте свойство [`subject`](#subject-stringsubjectjavascriptapioutlook15officesubject).</span><span class="sxs-lookup"><span data-stu-id="23147-p122">The normalizedSubject property gets the subject of the item, with any standard prefixes (such as `RE:` and `FW:`) that are added by email programs. To get the subject of the item with the prefixes intact, use the [`subject`](#subject-stringsubjectjavascriptapioutlook15officesubject) property.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-450">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-450">Type:</span></span>

*   <span data-ttu-id="23147-451">String</span><span class="sxs-lookup"><span data-stu-id="23147-451">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-452">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-452">Requirements</span></span>

|<span data-ttu-id="23147-453">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-453">Requirement</span></span>| <span data-ttu-id="23147-454">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-454">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-455">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-455">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-456">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-456">1.0</span></span>|
|[<span data-ttu-id="23147-457">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-457">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-458">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-458">ReadItem</span></span>|
|[<span data-ttu-id="23147-459">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-459">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-460">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-460">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-461">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-461">Example</span></span>

```
var normalizedSubject = Office.context.mailbox.item.normalizedSubject;
```

####  <a name="notificationmessages-notificationmessagesjavascriptapioutlook15officenotificationmessages"></a><span data-ttu-id="23147-462">notificationMessages :[NotificationMessages](/javascript/api/outlook_1_5/office.notificationmessages)</span><span class="sxs-lookup"><span data-stu-id="23147-462">notificationMessages :[NotificationMessages](/javascript/api/outlook_1_5/office.notificationmessages)</span></span>

<span data-ttu-id="23147-463">Получает сообщения уведомления для элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-463">Gets the notification messages for an item.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-464">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-464">Type:</span></span>

*   [<span data-ttu-id="23147-465">NotificationMessages</span><span class="sxs-lookup"><span data-stu-id="23147-465">NotificationMessages</span></span>](/javascript/api/outlook_1_5/office.notificationmessages)

##### <a name="requirements"></a><span data-ttu-id="23147-466">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-466">Requirements</span></span>

|<span data-ttu-id="23147-467">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-467">Requirement</span></span>| <span data-ttu-id="23147-468">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-468">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-469">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-469">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-470">1.3</span><span class="sxs-lookup"><span data-stu-id="23147-470">1.3</span></span>|
|[<span data-ttu-id="23147-471">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-471">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-472">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-472">ReadItem</span></span>|
|[<span data-ttu-id="23147-473">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-473">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-474">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-474">Compose or read</span></span>|

####  <a name="optionalattendees-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients"></a><span data-ttu-id="23147-475">optionalAttendees :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-475">optionalAttendees :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

<span data-ttu-id="23147-476">Предоставляет доступ к необязательным участникам события.</span><span class="sxs-lookup"><span data-stu-id="23147-476">Provides access to the optional attendees of an event.</span></span> <span data-ttu-id="23147-477">Уровень доступа и тип объекта, зависит от режима текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-477">The type of object and level of access depends on the mode of the current item.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-478">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-478">Read mode</span></span>

<span data-ttu-id="23147-479">Свойство `optionalAttendees` возвращает массив, содержащий объект `EmailAddressDetails` для каждого необязательного участника собрания.</span><span class="sxs-lookup"><span data-stu-id="23147-479">The `optionalAttendees` property returns an array that contains an `EmailAddressDetails` object for each optional attendee to the meeting.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-480">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-480">Compose mode</span></span>

<span data-ttu-id="23147-481">`optionalAttendees` Возвращает свойство `Recipients` объект, предоставляющий методы для получения или обновления необязательных участников собрания.</span><span class="sxs-lookup"><span data-stu-id="23147-481">The `optionalAttendees` property returns a `Recipients` object that provides methods to get or update the optional attendees for a meeting.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-482">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-482">Type:</span></span>

*   <span data-ttu-id="23147-483">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-483">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-484">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-484">Requirements</span></span>

|<span data-ttu-id="23147-485">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-485">Requirement</span></span>| <span data-ttu-id="23147-486">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-486">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-487">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-487">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-488">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-488">1.0</span></span>|
|[<span data-ttu-id="23147-489">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-489">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-490">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-490">ReadItem</span></span>|
|[<span data-ttu-id="23147-491">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-491">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-492">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-492">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-493">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-493">Example</span></span>

```
Office.context.mailbox.item.optionalAttendees.setAsync( ['alice@contoso.com', 'bob@contoso.com'] );
Office.context.mailbox.item.optionalAttendees.addAsync( ['jason@contoso.com'] );
Office.context.mailbox.item.optionalAttendees.getAsync(callback);

function callback(asyncResult) {
  var arrayOfOptionalAttendeesRecipients = asyncResult.value;
}
```

#### <a name="organizer-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails"></a><span data-ttu-id="23147-494">organizer :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span><span class="sxs-lookup"><span data-stu-id="23147-494">organizer :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span></span>

<span data-ttu-id="23147-p124">Получает электронный адрес организатора указанного собрания. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p124">Gets the email address of the meeting organizer for a specified meeting. Read mode only.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-497">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-497">Type:</span></span>

*   [<span data-ttu-id="23147-498">EmailAddressDetails</span><span class="sxs-lookup"><span data-stu-id="23147-498">EmailAddressDetails</span></span>](/javascript/api/outlook_1_5/office.emailaddressdetails)

##### <a name="requirements"></a><span data-ttu-id="23147-499">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-499">Requirements</span></span>

|<span data-ttu-id="23147-500">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-500">Requirement</span></span>| <span data-ttu-id="23147-501">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-501">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-502">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-502">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-503">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-503">1.0</span></span>|
|[<span data-ttu-id="23147-504">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-504">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-505">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-505">ReadItem</span></span>|
|[<span data-ttu-id="23147-506">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-506">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-507">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-507">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-508">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-508">Example</span></span>

```
var organizerName = Office.context.mailbox.item.organizer.displayName;
var organizerAddress = Office.context.mailbox.item.organizer.emailAddress;
```

####  <a name="requiredattendees-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients"></a><span data-ttu-id="23147-509">requiredAttendees :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-509">requiredAttendees :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

<span data-ttu-id="23147-510">Предоставляет доступ к обязательным участникам события.</span><span class="sxs-lookup"><span data-stu-id="23147-510">Provides access to the required attendees of an event.</span></span> <span data-ttu-id="23147-511">Уровень доступа и тип объекта, зависит от режима текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-511">The type of object and level of access depends on the mode of the current item.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-512">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-512">Read mode</span></span>

<span data-ttu-id="23147-513">Свойство `requiredAttendees` возвращает массив, содержащий объект `EmailAddressDetails` для каждого обязательного участника собрания.</span><span class="sxs-lookup"><span data-stu-id="23147-513">The `requiredAttendees` property returns an array that contains an `EmailAddressDetails` object for each required attendee to the meeting.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-514">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-514">Compose mode</span></span>

<span data-ttu-id="23147-515">`requiredAttendees` Возвращает свойство `Recipients` объект, предоставляющий методы для получения или обновления обязательных участников собрания.</span><span class="sxs-lookup"><span data-stu-id="23147-515">The `requiredAttendees` property returns a `Recipients` object that provides methods to get or update the required attendees for a meeting.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-516">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-516">Type:</span></span>

*   <span data-ttu-id="23147-517">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-517">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-518">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-518">Requirements</span></span>

|<span data-ttu-id="23147-519">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-519">Requirement</span></span>| <span data-ttu-id="23147-520">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-520">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-521">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-521">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-522">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-522">1.0</span></span>|
|[<span data-ttu-id="23147-523">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-523">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-524">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-524">ReadItem</span></span>|
|[<span data-ttu-id="23147-525">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-525">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-526">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-526">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-527">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-527">Example</span></span>

```
Office.context.mailbox.item.requiredAttendees.setAsync( ['alice@contoso.com', 'bob@contoso.com'] );
Office.context.mailbox.item.requiredAttendees.addAsync( ['jason@contoso.com'] );
Office.context.mailbox.item.requiredAttendees.getAsync(callback);

function callback(asyncResult) {
  var arrayOfRequiredAttendeesRecipients = asyncResult.value;
}
```

#### <a name="sender-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails"></a><span data-ttu-id="23147-528">sender :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span><span class="sxs-lookup"><span data-stu-id="23147-528">sender :[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)</span></span>

<span data-ttu-id="23147-p126">Получает электронный адрес отправителя электронного сообщения. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="23147-p126">Gets the email address of the sender of an email message. Read mode only.</span></span>

<span data-ttu-id="23147-p127">Свойства [`from`](#from-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) и `sender` представляют одно лицо, если сообщение не отправлено представителем. В противном случае свойство `from` представляет лицо, делегировавшее полномочия, а свойство sender — представителя.</span><span class="sxs-lookup"><span data-stu-id="23147-p127">The [`from`](#from-emailaddressdetailsjavascriptapioutlook15officeemailaddressdetails) and `sender` properties represent the same person unless the message is sent by a delegate. In that case, the `from` property represents the delegator, and the sender property represents the delegate.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-533">`recipientType` Свойства `EmailAddressDetails` объект в `sender` — это свойство `undefined`.</span><span class="sxs-lookup"><span data-stu-id="23147-533">The `recipientType` property of the `EmailAddressDetails` object in the `sender` property is `undefined`.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-534">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-534">Type:</span></span>

*   [<span data-ttu-id="23147-535">EmailAddressDetails</span><span class="sxs-lookup"><span data-stu-id="23147-535">EmailAddressDetails</span></span>](/javascript/api/outlook_1_5/office.emailaddressdetails)

##### <a name="requirements"></a><span data-ttu-id="23147-536">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-536">Requirements</span></span>

|<span data-ttu-id="23147-537">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-537">Requirement</span></span>| <span data-ttu-id="23147-538">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-538">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-539">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-539">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-540">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-540">1.0</span></span>|
|[<span data-ttu-id="23147-541">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-541">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-542">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-542">ReadItem</span></span>|
|[<span data-ttu-id="23147-543">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-543">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-544">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-544">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-545">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-545">Example</span></span>

```
var senderName = Office.context.mailbox.item.sender.displayName;
var senderAddress = Office.context.mailbox.item.sender.emailAddress;
```

####  <a name="start-datetimejavascriptapioutlook15officetime"></a><span data-ttu-id="23147-546">start :Date|[Time](/javascript/api/outlook_1_5/office.time)</span><span class="sxs-lookup"><span data-stu-id="23147-546">start :Date|[Time](/javascript/api/outlook_1_5/office.time)</span></span>

<span data-ttu-id="23147-547">Получает или задает дату и время начала встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-547">Gets or sets the date and time that the appointment is to begin.</span></span>

<span data-ttu-id="23147-p128">Свойство `start` представлено в виде значения даты и времени в формате UTC. Это значение можно преобразовать в местные значения даты и времени клиента с помощью метода [`convertToLocalClientTime`](office.context.mailbox.md#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime).</span><span class="sxs-lookup"><span data-stu-id="23147-p128">The `start` property is expressed as a Coordinated Universal Time (UTC) date and time value. You can use the [`convertToLocalClientTime`](office.context.mailbox.md#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook15officelocalclienttime) method to convert the value to the client’s local date and time.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-550">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-550">Read mode</span></span>

<span data-ttu-id="23147-551">Свойство `start` возвращает объект `Date`.</span><span class="sxs-lookup"><span data-stu-id="23147-551">The `start` property returns a `Date` object.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-552">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-552">Compose mode</span></span>

<span data-ttu-id="23147-553">Свойство `start` возвращает объект `Time`.</span><span class="sxs-lookup"><span data-stu-id="23147-553">The `start` property returns a `Time` object.</span></span>

<span data-ttu-id="23147-554">Если вы задаете время начала с помощью метода [`Time.setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-), необходимо использовать метод [`convertToUtcClientTime`](office.context.mailbox.md#converttoutcclienttimeinput--date) для преобразования местного времени на клиенте в формат UTC для сервера.</span><span class="sxs-lookup"><span data-stu-id="23147-554">When you use the [`Time.setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) method to set the start time, you should use the [`convertToUtcClientTime`](office.context.mailbox.md#converttoutcclienttimeinput--date) method to convert the local time on the client to UTC for the server.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-555">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-555">Type:</span></span>

*   <span data-ttu-id="23147-556">Date | [Time](/javascript/api/outlook_1_5/office.time)</span><span class="sxs-lookup"><span data-stu-id="23147-556">Date | [Time](/javascript/api/outlook_1_5/office.time)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-557">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-557">Requirements</span></span>

|<span data-ttu-id="23147-558">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-558">Requirement</span></span>| <span data-ttu-id="23147-559">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-559">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-560">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-560">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-561">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-561">1.0</span></span>|
|[<span data-ttu-id="23147-562">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-562">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-563">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-563">ReadItem</span></span>|
|[<span data-ttu-id="23147-564">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-564">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-565">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-565">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-566">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-566">Example</span></span>

<span data-ttu-id="23147-567">В примере ниже с помощью метода [`setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) объекта `Time` задается время начала встречи в режиме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-567">The following example sets the start time of an appointment in compose mode by using the [`setAsync`](/javascript/api/outlook_1_5/office.time#setasync-datetime--options--callback-) method of the `Time` object.</span></span>

```
var startTime = new Date("3/14/2015");
var options = {
  // Pass information that can be used
  // in the callback
     asyncContext: {verb:"Set"}
}
Office.context.mailbox.item.start.setAsync(startTime, options, function(result) {
  if (result.error) {
    console.debug(result.error);
  } else {
    // Access the asyncContext that was passed to the setAsync function
    console.debug("Start Time " + result.asyncContext.verb);
  }
});
```

####  <a name="subject-stringsubjectjavascriptapioutlook15officesubject"></a><span data-ttu-id="23147-568">subject :String|[Subject](/javascript/api/outlook_1_5/office.subject)</span><span class="sxs-lookup"><span data-stu-id="23147-568">subject :String|[Subject](/javascript/api/outlook_1_5/office.subject)</span></span>

<span data-ttu-id="23147-569">Получает или задает описание, которое отображается в поле темы элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-569">Gets or sets the description that appears in the subject field of an item.</span></span>

<span data-ttu-id="23147-570">Свойство `subject` получает или задает всю тему элемента для отправки с почтового сервера.</span><span class="sxs-lookup"><span data-stu-id="23147-570">The `subject` property gets or sets the entire subject of the item, as sent by the email server.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-571">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-571">Read mode</span></span>

<span data-ttu-id="23147-p129">Свойство `subject` возвращает строку. С помощью свойства [`normalizedSubject`](#normalizedsubject-string) можно получить тему без начальных префиксов, таких как `RE:` и `FW:`.</span><span class="sxs-lookup"><span data-stu-id="23147-p129">The `subject` property returns a string. Use the [`normalizedSubject`](#normalizedsubject-string) property to get the subject minus any leading prefixes such as `RE:` and `FW:`.</span></span>

```
var subject = Office.context.mailbox.item.subject;
```

##### <a name="compose-mode"></a><span data-ttu-id="23147-574">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-574">Compose mode</span></span>

<span data-ttu-id="23147-575">Свойство `subject` возвращает объект `Subject`, который предоставляет методы для получения и задания темы.</span><span class="sxs-lookup"><span data-stu-id="23147-575">The `subject` property returns a `Subject` object that provides methods to get and set the subject.</span></span>

```
Office.context.mailbox.item.subject.getAsync(callback);

function callback(asyncResult) {
  var subject = asyncResult.value;
}
```

##### <a name="type"></a><span data-ttu-id="23147-576">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-576">Type:</span></span>

*   <span data-ttu-id="23147-577">String | [Subject](/javascript/api/outlook_1_5/office.subject)</span><span class="sxs-lookup"><span data-stu-id="23147-577">String | [Subject](/javascript/api/outlook_1_5/office.subject)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-578">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-578">Requirements</span></span>

|<span data-ttu-id="23147-579">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-579">Requirement</span></span>| <span data-ttu-id="23147-580">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-580">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-581">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-581">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-582">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-582">1.0</span></span>|
|[<span data-ttu-id="23147-583">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-583">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-584">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-584">ReadItem</span></span>|
|[<span data-ttu-id="23147-585">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-585">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-586">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-586">Compose or read</span></span>|

####  <a name="to-arrayemailaddressdetailsjavascriptapioutlook15officeemailaddressdetailsrecipientsjavascriptapioutlook15officerecipients"></a><span data-ttu-id="23147-587">Чтобы: массив. <[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[получателей](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-587">to :Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)>|[Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

<span data-ttu-id="23147-588">Предоставляет доступ к получателей в строке **Кому** сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-588">Provides access to the recipients on the **To** line of a message.</span></span> <span data-ttu-id="23147-589">Уровень доступа и тип объекта, зависит от режима текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-589">The type of object and level of access depends on the mode of the current item.</span></span>

##### <a name="read-mode"></a><span data-ttu-id="23147-590">Режим чтения</span><span class="sxs-lookup"><span data-stu-id="23147-590">Read mode</span></span>

<span data-ttu-id="23147-p131">Свойство `to` возвращает массив, содержащий объект `EmailAddressDetails` для каждого получателя в строке **Кому** сообщения. Коллекция может включать не более 100 элементов.</span><span class="sxs-lookup"><span data-stu-id="23147-p131">The `to` property returns an array that contains an `EmailAddressDetails` object for each recipient listed on the **To** line of the message. The collection is limited to a maximum of 100 members.</span></span>

##### <a name="compose-mode"></a><span data-ttu-id="23147-593">Режим создания</span><span class="sxs-lookup"><span data-stu-id="23147-593">Compose mode</span></span>

<span data-ttu-id="23147-594">`to` Возвращает свойство `Recipients` объект, предоставляющий методы для получения или обновления получателей в строке **Кому** сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-594">The `to` property returns a `Recipients` object that provides methods to get or update the recipients on the **To** line of the message.</span></span>

##### <a name="type"></a><span data-ttu-id="23147-595">Тип:</span><span class="sxs-lookup"><span data-stu-id="23147-595">Type:</span></span>

*   <span data-ttu-id="23147-596">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span><span class="sxs-lookup"><span data-stu-id="23147-596">Array.<[EmailAddressDetails](/javascript/api/outlook_1_5/office.emailaddressdetails)> | [Recipients](/javascript/api/outlook_1_5/office.recipients)</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-597">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-597">Requirements</span></span>

|<span data-ttu-id="23147-598">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-598">Requirement</span></span>| <span data-ttu-id="23147-599">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-599">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-600">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-600">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-601">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-601">1.0</span></span>|
|[<span data-ttu-id="23147-602">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-602">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-603">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-603">ReadItem</span></span>|
|[<span data-ttu-id="23147-604">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-604">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-605">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-605">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-606">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-606">Example</span></span>

```
Office.context.mailbox.item.to.setAsync( ['alice@contoso.com', 'bob@contoso.com'] );
Office.context.mailbox.item.to.addAsync( ['jason@contoso.com'] );
Office.context.mailbox.item.to.getAsync(callback);

function callback(asyncResult) {
  var arrayOfToRecipients = asyncResult.value;
}
```

### <a name="methods"></a><span data-ttu-id="23147-607">Методы</span><span class="sxs-lookup"><span data-stu-id="23147-607">Methods</span></span>

####  <a name="addfileattachmentasyncuri-attachmentname-options-callback"></a><span data-ttu-id="23147-608">addFileAttachmentAsync(uri, attachmentName, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="23147-608">addFileAttachmentAsync(uri, attachmentName, [options], [callback])</span></span>

<span data-ttu-id="23147-609">Добавляет файл в сообщение или встречу в качестве вложения.</span><span class="sxs-lookup"><span data-stu-id="23147-609">Adds a file to a message or appointment as an attachment.</span></span>

<span data-ttu-id="23147-610">Метод `addFileAttachmentAsync` передает файл по указанному универсальному коду ресурса (URI) и вкладывает его в элемент в форме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-610">The `addFileAttachmentAsync` method uploads the file at the specified URI and attaches it to the item in the compose form.</span></span>

<span data-ttu-id="23147-611">Идентификатор можно последовательно использовать с методом [`removeAttachmentAsync`](#removeattachmentasyncattachmentid-options-callback), чтобы удалить вложение, добавленное во время текущего сеанса.</span><span class="sxs-lookup"><span data-stu-id="23147-611">You can subsequently use the identifier with the [`removeAttachmentAsync`](#removeattachmentasyncattachmentid-options-callback) method to remove the attachment in the same session.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-612">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-612">Parameters:</span></span>

|<span data-ttu-id="23147-613">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-613">Name</span></span>| <span data-ttu-id="23147-614">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-614">Type</span></span>| <span data-ttu-id="23147-615">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-615">Attributes</span></span>| <span data-ttu-id="23147-616">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-616">Description</span></span>|
|---|---|---|---|
|`uri`| <span data-ttu-id="23147-617">String</span><span class="sxs-lookup"><span data-stu-id="23147-617">String</span></span>||<span data-ttu-id="23147-p132">Универсальный код ресурса (URI), представляющий расположение файла, который нужно вложить в сообщение или встречу. Максимальная длина — 2048 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p132">The URI that provides the location of the file to attach to the message or appointment. The maximum length is 2048 characters.</span></span>|
|`attachmentName`| <span data-ttu-id="23147-620">String</span><span class="sxs-lookup"><span data-stu-id="23147-620">String</span></span>||<span data-ttu-id="23147-p133">Имя вложения, которое отображается при передаче вложения. Максимальная длина — 255 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p133">The name of the attachment that is shown while the attachment is uploading. The maximum length is 255 characters.</span></span>|
|`options`| <span data-ttu-id="23147-623">Object</span><span class="sxs-lookup"><span data-stu-id="23147-623">Object</span></span>| <span data-ttu-id="23147-624">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-624">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-625">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-625">An object literal that contains one or more of the following properties.</span></span>|
| `options.asyncContext` | <span data-ttu-id="23147-626">Object</span><span class="sxs-lookup"><span data-stu-id="23147-626">Object</span></span> | <span data-ttu-id="23147-627">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-627">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-628">В методе обратного вызова разработчики могут указать любой объект, к которому необходимо получить доступ.</span><span class="sxs-lookup"><span data-stu-id="23147-628">Developers can provide any object they wish to access in the callback method.</span></span> |
| `options.isInline` | <span data-ttu-id="23147-629">Boolean</span><span class="sxs-lookup"><span data-stu-id="23147-629">Boolean</span></span> | <span data-ttu-id="23147-630">&lt;Необязательный&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-630">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-631">Значение `true` указывает на то, что вложение будет встроено в текст сообщения и не должно отображаться в списке вложений.</span><span class="sxs-lookup"><span data-stu-id="23147-631">If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
|`callback`| <span data-ttu-id="23147-632">function</span><span class="sxs-lookup"><span data-stu-id="23147-632">function</span></span>| <span data-ttu-id="23147-633">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-633">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-634">После выполнения метода функция, переданная в параметре `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-634">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span> <br/><span data-ttu-id="23147-635">После успешного выполнения идентификатор вложения будет представлен в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="23147-635">On success, the attachment identifier will be provided in the `asyncResult.value` property.</span></span><br/><span data-ttu-id="23147-636">Если добавить вложение не удастся, объект `asyncResult` будет содержать объект `Error` с описанием ошибки.</span><span class="sxs-lookup"><span data-stu-id="23147-636">If uploading the attachment fails, the `asyncResult` object will contain an `Error` object that provides a description of the error.</span></span>|

##### <a name="errors"></a><span data-ttu-id="23147-637">Ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-637">Errors</span></span>

| <span data-ttu-id="23147-638">Код ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-638">Error code</span></span> | <span data-ttu-id="23147-639">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-639">Description</span></span> |
|------------|-------------|
| `AttachmentSizeExceeded` | <span data-ttu-id="23147-640">Вложение превышает максимальный размер.</span><span class="sxs-lookup"><span data-stu-id="23147-640">The attachment is larger than allowed.</span></span> |
| `FileTypeNotSupported` | <span data-ttu-id="23147-641">Расширение вложения не поддерживается.</span><span class="sxs-lookup"><span data-stu-id="23147-641">The attachment has an extension that is not allowed.</span></span> |
| `NumberOfAttachmentsExceeded` | <span data-ttu-id="23147-642">Сообщение или встреча содержат слишком много вложений.</span><span class="sxs-lookup"><span data-stu-id="23147-642">The message or appointment has too many attachments.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-643">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-643">Requirements</span></span>

|<span data-ttu-id="23147-644">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-644">Requirement</span></span>| <span data-ttu-id="23147-645">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-645">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-646">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-646">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-647">1.1</span><span class="sxs-lookup"><span data-stu-id="23147-647">1.1</span></span>|
|[<span data-ttu-id="23147-648">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-648">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-649">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-649">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-650">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-650">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-651">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-651">Compose</span></span>|

##### <a name="examples"></a><span data-ttu-id="23147-652">Примеры</span><span class="sxs-lookup"><span data-stu-id="23147-652">Examples</span></span>

```js
function callback(result) {
  if (result.error) {
    showMessage(result.error);
  } else {
    showMessage("Attachment added");
  }
}

function addAttachment() {
  // The values in asyncContext can be accessed in the callback
  var options = { 'asyncContext': { var1: 1, var2: 2 } };

  var attachmentURL = "https://contoso.com/rtm/icon.png";
  Office.context.mailbox.item.addFileAttachmentAsync(attachmentURL, attachmentURL, options, callback);
}
```

<span data-ttu-id="23147-653">В приведенном ниже примере файл изображения добавляется в качестве встроенного вложения, а ссылка на вложение добавляется в текст сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-653">The following example adds an image file as an inline attachment and references the attachment in the message body.</span></span>

```js
Office.context.mailbox.item.addFileAttachmentAsync
(
  "http://i.imgur.com/WJXklif.png",
  "cute_bird.png",
  {
    isInline: true
  },
  function (asyncResult) {
    Office.context.mailbox.item.body.setAsync(
      "<p>Here's a cute bird!</p><img src='cid:cute_bird.png'>",
      {
        "coercionType": "html"
      },
      function (asyncResult) {
        
      }
    );
  }
);
```

####  <a name="additemattachmentasyncitemid-attachmentname-options-callback"></a><span data-ttu-id="23147-654">addItemAttachmentAsync(itemId, attachmentName, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="23147-654">addItemAttachmentAsync(itemId, attachmentName, [options], [callback])</span></span>

<span data-ttu-id="23147-655">Добавляет к сообщению элемент Exchange, например сообщение, в виде вложения.</span><span class="sxs-lookup"><span data-stu-id="23147-655">Adds an Exchange item, such as a message, as an attachment to the message or appointment.</span></span>

<span data-ttu-id="23147-p134">С помощью метода `addItemAttachmentAsync` можно в элемент формы создания вложить элемент с указанным идентификатором Exchange. Если указать метод обратного вызова, то этот метод вызывается с помощью параметра `asyncResult`, который содержит идентификатор вложения или код, указывающий на ошибки, которые произошли при вложении элемента. При необходимости можно использовать параметр `options` для передачи сведений о состоянии методу обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-p134">The `addItemAttachmentAsync` method attaches the item with the specified Exchange identifier to the item in the compose form. If you specify a callback method, the method is called with one parameter, `asyncResult`, which contains either the attachment identifier or a code that indicates any error that occurred while attaching the item. You can use the `options` parameter to pass state information to the callback method, if needed.</span></span>

<span data-ttu-id="23147-659">Идентификатор можно последовательно использовать с методом [`removeAttachmentAsync`](#removeattachmentasyncattachmentid-options-callback), чтобы удалить вложение, добавленное во время текущего сеанса.</span><span class="sxs-lookup"><span data-stu-id="23147-659">You can subsequently use the identifier with the [`removeAttachmentAsync`](#removeattachmentasyncattachmentid-options-callback) method to remove the attachment in the same session.</span></span>

<span data-ttu-id="23147-660">Если надстройки Office работает в Outlook Web App, `addItemAttachmentAsync` метод могут прикреплять элементов для элементов, отличных от элемента, который вы изменяете; Однако это не поддерживается и не рекомендуется.</span><span class="sxs-lookup"><span data-stu-id="23147-660">If your Office Add-in is running in Outlook Web App, the `addItemAttachmentAsync` method can attach items to items other than the item that you are editing; however, this is not supported and is not recommended.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-661">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-661">Parameters:</span></span>

|<span data-ttu-id="23147-662">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-662">Name</span></span>| <span data-ttu-id="23147-663">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-663">Type</span></span>| <span data-ttu-id="23147-664">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-664">Attributes</span></span>| <span data-ttu-id="23147-665">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-665">Description</span></span>|
|---|---|---|---|
|`itemId`| <span data-ttu-id="23147-666">String</span><span class="sxs-lookup"><span data-stu-id="23147-666">String</span></span>||<span data-ttu-id="23147-p135">Идентификатор Exchange для вкладываемого элемента. Максимальная длина — 100 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p135">The Exchange identifier of the item to attach. The maximum length is 100 characters.</span></span>|
|`attachmentName`| <span data-ttu-id="23147-669">String</span><span class="sxs-lookup"><span data-stu-id="23147-669">String</span></span>||<span data-ttu-id="23147-p136">Тема вкладываемого элемента. Максимальная длина — 255 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p136">The sujbect of the item to be attached. The maximum length is 255 characters.</span></span>|
|`options`| <span data-ttu-id="23147-672">Object</span><span class="sxs-lookup"><span data-stu-id="23147-672">Object</span></span>| <span data-ttu-id="23147-673">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-673">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-674">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-674">An object literal that contains one or more of the following properties.</span></span>|
|`options.asyncContext`| <span data-ttu-id="23147-675">Object</span><span class="sxs-lookup"><span data-stu-id="23147-675">Object</span></span>| <span data-ttu-id="23147-676">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-676">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-677">Разработчики могут указать любой объект, к которому необходимо получить доступ, в методе обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-677">Developers can provide any object they wish to access in the callback method.</span></span>|
|`callback`| <span data-ttu-id="23147-678">function</span><span class="sxs-lookup"><span data-stu-id="23147-678">function</span></span>| <span data-ttu-id="23147-679">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-679">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-680">После выполнения метода функция, переданная в параметре `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-680">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span> <br/><span data-ttu-id="23147-681">После успешного выполнения идентификатор вложения будет представлен в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="23147-681">On success, the attachment identifier will be provided in the `asyncResult.value` property.</span></span><br/><span data-ttu-id="23147-682">Если добавить вложение не удастся, объект `asyncResult` будет содержать объект `Error` с описанием ошибки.</span><span class="sxs-lookup"><span data-stu-id="23147-682">If adding the attachment fails, the `asyncResult` object will contain an `Error` object that provides a description of the error.</span></span>|

##### <a name="errors"></a><span data-ttu-id="23147-683">Ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-683">Errors</span></span>

| <span data-ttu-id="23147-684">Код ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-684">Error code</span></span> | <span data-ttu-id="23147-685">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-685">Description</span></span> |
|------------|-------------|
| `NumberOfAttachmentsExceeded` | <span data-ttu-id="23147-686">Сообщение или встреча содержат слишком много вложений.</span><span class="sxs-lookup"><span data-stu-id="23147-686">The message or appointment has too many attachments.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-687">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-687">Requirements</span></span>

|<span data-ttu-id="23147-688">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-688">Requirement</span></span>| <span data-ttu-id="23147-689">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-689">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-690">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-690">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-691">1.1</span><span class="sxs-lookup"><span data-stu-id="23147-691">1.1</span></span>|
|[<span data-ttu-id="23147-692">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-692">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-693">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-693">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-694">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-694">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-695">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-695">Compose</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-696">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-696">Example</span></span>

<span data-ttu-id="23147-697">В следующем примере существующий элемент Outlook добавляется в виде вложения с именем `My Attachment`.</span><span class="sxs-lookup"><span data-stu-id="23147-697">The following example adds an existing Outlook item as an attachment with the name `My Attachment`.</span></span>

```
function callback(result) {
  if (result.error) {
    showMessage(result.error);
  } else {
    showMessage("Attachment added");
  }
}

function addAttachment() {
  // EWS ID of item to attach
  // (Shortened for readability)
  var itemId = "AAMkADI1...AAA=";

  // The values in asyncContext can be accessed in the callback
  var options = { 'asyncContext': { var1: 1, var2: 2 } };

  Office.context.mailbox.item.addItemAttachmentAsync(itemId, "My Attachment", options, callback);
}
```

####  <a name="close"></a><span data-ttu-id="23147-698">close()</span><span class="sxs-lookup"><span data-stu-id="23147-698">close()</span></span>

<span data-ttu-id="23147-699">Закрывает текущий создаваемый элемент.</span><span class="sxs-lookup"><span data-stu-id="23147-699">Closes the current item that is being composed.</span></span>

<span data-ttu-id="23147-p137">Работа метода `close` зависит от текущего состояния создаваемого элемента. Если элемент содержит несохраненные изменения, клиент предложит пользователю сохранить или отклонить их либо отменить действие закрытия.</span><span class="sxs-lookup"><span data-stu-id="23147-p137">The behavior of the `close` method depends on the current state of the item being composed. If the item has unsaved changes, the client prompts the user to save, discard, or cancel the close action.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-702">В Outlook в Интернете, если элемент является ли он встречей, и он ранее был сохранен с помощью `saveAsync`, то пользователю будет предложено сохранение, удаление или Отмена даже в том случае, если изменений внесено не было с элемента последнего сохранения.</span><span class="sxs-lookup"><span data-stu-id="23147-702">In Outlook on the web, if the item is an appointment and it has previously been saved using `saveAsync`, the user is prompted to save, discard, or cancel even if no changes have occurred since the item was last saved.</span></span>

<span data-ttu-id="23147-703">Если в клиенте Outlook для настольных ПК сообщение представляет собой ответ в тексте, метод `close` не работает.</span><span class="sxs-lookup"><span data-stu-id="23147-703">In the Outlook desktop client, if the message is an inline reply, the `close` method has no effect.</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-704">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-704">Requirements</span></span>

|<span data-ttu-id="23147-705">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-705">Requirement</span></span>| <span data-ttu-id="23147-706">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-706">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-707">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-707">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-708">1.3</span><span class="sxs-lookup"><span data-stu-id="23147-708">1.3</span></span>|
|[<span data-ttu-id="23147-709">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-709">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-710">Restricted</span><span class="sxs-lookup"><span data-stu-id="23147-710">Restricted</span></span>|
|[<span data-ttu-id="23147-711">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-711">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-712">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-712">Compose</span></span>|

#### <a name="displayreplyallformformdata"></a><span data-ttu-id="23147-713">displayReplyAllForm(formData)</span><span class="sxs-lookup"><span data-stu-id="23147-713">displayReplyAllForm(formData)</span></span>

<span data-ttu-id="23147-714">Отображает форму ответа, включающую отправителя и всех получателей выбранного сообщения или организатора и всех участников выбранной встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-714">Displays a reply form that includes the sender and all recipients of the selected message or the organizer and all attendees of the selected appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-715">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-715">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="23147-716">В Outlook Web App форма ответа отображается в виде всплывающей формы в представлении с 3 либо 1 или 2 колонками.</span><span class="sxs-lookup"><span data-stu-id="23147-716">In Outlook Web App, the reply form is displayed as a pop-out form in the 3-column view and a pop-up form in the 2- or 1-column view.</span></span>

<span data-ttu-id="23147-717">Если любой строковый параметр превышает указанные для него ограничения, `displayReplyAllForm` возвращает исключение.</span><span class="sxs-lookup"><span data-stu-id="23147-717">If any of the string parameters exceed their limits, `displayReplyAllForm` throws an exception.</span></span>

<span data-ttu-id="23147-p138">Если в параметре `formData.attachments` указаны вложения, Outlook и Outlook Web App пытаются скачать их и вложить в форму ответа. Если какие-либо вложения добавить не удается, в форме отображается сообщение об ошибке. Если сообщения об ошибках не предусмотрены, то они не отображаются.</span><span class="sxs-lookup"><span data-stu-id="23147-p138">When attachments are specified in the `formData.attachments` parameter, Outlook and Outlook Web App attempt to download all attachments and attach them to the reply form. If any attachments fail to be added, an error is shown in the form UI. If this isn't possible, then no error message is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-721">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-721">Parameters:</span></span>

| <span data-ttu-id="23147-722">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-722">Name</span></span> | <span data-ttu-id="23147-723">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-723">Type</span></span> | <span data-ttu-id="23147-724">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-724">Attributes</span></span> | <span data-ttu-id="23147-725">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-725">Description</span></span> |
|---|---|---|---|
|`formData`| <span data-ttu-id="23147-726">String &#124; Object</span><span class="sxs-lookup"><span data-stu-id="23147-726">String &#124; Object</span></span>| |<span data-ttu-id="23147-p139">Строка, содержащая текст и HTML-код, представляющие собой основной текст формы ответа. Максимальный размер строки — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="23147-p139">A string that contains text and HTML and that represents the body of the reply form. The string is limited to 32 KB.</span></span><br/><span data-ttu-id="23147-729">**ИЛИ**</span><span class="sxs-lookup"><span data-stu-id="23147-729">**OR**</span></span><br/><span data-ttu-id="23147-p140">Объект, который содержит текст или данные вложения и функцию обратного вызова. Ниже представлено определение этого объекта.</span><span class="sxs-lookup"><span data-stu-id="23147-p140">An object that contains body or attachment data and a callback function. The object is defined as follows.</span></span> |
| `formData.htmlBody` | <span data-ttu-id="23147-732">String</span><span class="sxs-lookup"><span data-stu-id="23147-732">String</span></span> | <span data-ttu-id="23147-733">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-733">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-p141">Строка, содержащая текст и HTML-код, представляющие собой основной текст формы ответа. Максимальный размер строки — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="23147-p141">A string that contains text and HTML and that represents the body of the reply form. The string is limited to 32 KB.</span></span>
| `formData.attachments` | <span data-ttu-id="23147-736">Array.&lt;Object&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-736">Array.&lt;Object&gt;</span></span> | <span data-ttu-id="23147-737">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-737">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-738">Массив объектов JSON, представляющих собой вложенные файлы или элементы.</span><span class="sxs-lookup"><span data-stu-id="23147-738">An array of JSON objects that are either file or item attachments.</span></span> |
| `formData.attachments.type` | <span data-ttu-id="23147-739">String</span><span class="sxs-lookup"><span data-stu-id="23147-739">String</span></span> | | <span data-ttu-id="23147-p142">Указывает тип вложения. Допустимые значения: `file` для вложенного файла и `item` для вложенного элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-p142">Indicates the type of attachment. Must be `file` for a file attachment or `item` for an item attachment.</span></span> |
| `formData.attachments.name` | <span data-ttu-id="23147-742">String</span><span class="sxs-lookup"><span data-stu-id="23147-742">String</span></span> | | <span data-ttu-id="23147-743">Строка, содержащая имя вложения, длиной до 255 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-743">A string that contains the name of the attachment, up to 255 characters in length.</span></span>|
| `formData.attachments.url` | <span data-ttu-id="23147-744">String</span><span class="sxs-lookup"><span data-stu-id="23147-744">String</span></span> | | <span data-ttu-id="23147-p143">Используется, только если свойству `type` задано значение `file`. URI расположения файла.</span><span class="sxs-lookup"><span data-stu-id="23147-p143">Only used if `type` is set to `file`. The URI of the location for the file.</span></span> |
| `formData.attachments.isInline` | <span data-ttu-id="23147-747">Boolean</span><span class="sxs-lookup"><span data-stu-id="23147-747">Boolean</span></span> | | <span data-ttu-id="23147-p144">Используется, только если свойству `type` задано значение `file`. Значение `true` указывает на то, что вложение будет встроено в текст сообщения и не должно отображаться в списке вложений.</span><span class="sxs-lookup"><span data-stu-id="23147-p144">Only used if `type` is set to `file`. If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
| `formData.attachments.itemId` | <span data-ttu-id="23147-750">String</span><span class="sxs-lookup"><span data-stu-id="23147-750">String</span></span> | | <span data-ttu-id="23147-p145">Используется, только если свойству `type` задано значение `item`. Идентификатор вложения EWS. Это строка длиной до 100 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p145">Only used if `type` is set to `item`. The EWS item id of the attachment. This is a string up to 100 characters.</span></span> |
| `callback` | <span data-ttu-id="23147-754">function</span><span class="sxs-lookup"><span data-stu-id="23147-754">function</span></span> | <span data-ttu-id="23147-755">&lt;Необязательный&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-755">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-756">По завершении работы метода функция, переданная параметру `callback`, вызывается с помощью одного параметра `asyncResult`, представляющего собой объект [AsyncResult](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-756">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [AsyncResult](/javascript/api/office/office.asyncresult) object.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-757">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-757">Requirements</span></span>

|<span data-ttu-id="23147-758">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-758">Requirement</span></span>| <span data-ttu-id="23147-759">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-759">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-760">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-760">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-761">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-761">1.0</span></span>|
|[<span data-ttu-id="23147-762">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-762">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-763">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-763">ReadItem</span></span>|
|[<span data-ttu-id="23147-764">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-764">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-765">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-765">Read</span></span>|

##### <a name="examples"></a><span data-ttu-id="23147-766">Примеры</span><span class="sxs-lookup"><span data-stu-id="23147-766">Examples</span></span>

<span data-ttu-id="23147-767">Приведенный ниже код передает строку в функцию `displayReplyAllForm`.</span><span class="sxs-lookup"><span data-stu-id="23147-767">The following code passes a string to the `displayReplyAllForm` function.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm('hello there');
Office.context.mailbox.item.displayReplyAllForm('<b>hello there</b>');
```

<span data-ttu-id="23147-768">Ответ с пустым текстом сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-768">Reply with an empty body.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm({});
```

<span data-ttu-id="23147-769">Ответ только с текстом сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-769">Reply with just a body.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm(
{
  'htmlBody' : 'hi'
});
```

<span data-ttu-id="23147-770">Ответ с текстом сообщения и вложенным файлом.</span><span class="sxs-lookup"><span data-stu-id="23147-770">Reply with a body and a file attachment.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : Office.MailboxEnums.AttachmentType.File,
      'name' : 'squirrel.png',
      'url' : 'http://i.imgur.com/sRgTlGR.jpg'
    }
  ]
});
```

<span data-ttu-id="23147-771">Ответ с текстом сообщения и вложенным элементом.</span><span class="sxs-lookup"><span data-stu-id="23147-771">Reply with a body and an item attachment.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : 'item',
      'name' : 'rand',
      'itemId' : Office.context.mailbox.item.itemId
    }
  ]
});
```

<span data-ttu-id="23147-772">Ответ с текстом сообщения, вложенным файлом, вложенным элементом и обратным вызовом.</span><span class="sxs-lookup"><span data-stu-id="23147-772">Reply with a body, file attachment, item attachment, and a callback.</span></span>

```
Office.context.mailbox.item.displayReplyAllForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : Office.MailboxEnums.AttachmentType.File,
      'name' : 'squirrel.png',
      'url' : 'http://i.imgur.com/sRgTlGR.jpg'
    },
    {
      'type' : 'item',
      'name' : 'rand',
      'itemId' : Office.context.mailbox.item.itemId
    }
  ],
  'callback' : function(asyncResult)
  {
    console.log(asyncResult.value);
  }
});
```

#### <a name="displayreplyformformdata"></a><span data-ttu-id="23147-773">displayReplyForm(formData)</span><span class="sxs-lookup"><span data-stu-id="23147-773">displayReplyForm(formData)</span></span>

<span data-ttu-id="23147-774">Отображает форму ответа, включающую только отправителя выбранного сообщения или организатора выбранной встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-774">Displays a reply form that includes only the sender of the selected message or the organizer of the selected appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-775">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-775">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="23147-776">В Outlook Web App форма ответа отображается в виде всплывающей формы в представлении с 3 либо 1 или 2 колонками.</span><span class="sxs-lookup"><span data-stu-id="23147-776">In Outlook Web App, the reply form is displayed as a pop-out form in the 3-column view and a pop-up form in the 2- or 1-column view.</span></span>

<span data-ttu-id="23147-777">Если любой строковый параметр превышает указанные для него ограничения, `displayReplyForm` возвращает исключение.</span><span class="sxs-lookup"><span data-stu-id="23147-777">If any of the string parameters exceed their limits, `displayReplyForm` throws an exception.</span></span>

<span data-ttu-id="23147-p146">Если в параметре `formData.attachments` указаны вложения, Outlook и Outlook Web App пытаются скачать их и вложить в форму ответа. Если какие-либо вложения добавить не удается, в форме отображается сообщение об ошибке. Если сообщения об ошибках не предусмотрены, то они не отображаются.</span><span class="sxs-lookup"><span data-stu-id="23147-p146">When attachments are specified in the `formData.attachments` parameter, Outlook and Outlook Web App attempt to download all attachments and attach them to the reply form. If any attachments fail to be added, an error is shown in the form UI. If this isn't possible, then no error message is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-781">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-781">Parameters:</span></span>

| <span data-ttu-id="23147-782">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-782">Name</span></span> | <span data-ttu-id="23147-783">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-783">Type</span></span> | <span data-ttu-id="23147-784">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-784">Attributes</span></span> | <span data-ttu-id="23147-785">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-785">Description</span></span> |
|---|---|---|---|
|`formData`| <span data-ttu-id="23147-786">String &#124; Object</span><span class="sxs-lookup"><span data-stu-id="23147-786">String &#124; Object</span></span>| | <span data-ttu-id="23147-p147">Строка, содержащая текст и HTML-код, представляющие собой основной текст формы ответа. Максимальный размер строки — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="23147-p147">A string that contains text and HTML and that represents the body of the reply form. The string is limited to 32 KB.</span></span><br/><span data-ttu-id="23147-789">**ИЛИ**</span><span class="sxs-lookup"><span data-stu-id="23147-789">**OR**</span></span><br/><span data-ttu-id="23147-p148">Объект, который содержит текст или данные вложения и функцию обратного вызова. Ниже представлено определение этого объекта.</span><span class="sxs-lookup"><span data-stu-id="23147-p148">An object that contains body or attachment data and a callback function. The object is defined as follows.</span></span> |
| `formData.htmlBody` | <span data-ttu-id="23147-792">String</span><span class="sxs-lookup"><span data-stu-id="23147-792">String</span></span> | <span data-ttu-id="23147-793">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-793">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-p149">Строка, содержащая текст и HTML-код, представляющие собой основной текст формы ответа. Максимальный размер строки — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="23147-p149">A string that contains text and HTML and that represents the body of the reply form. The string is limited to 32 KB.</span></span>
| `formData.attachments` | <span data-ttu-id="23147-796">Array.&lt;Object&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-796">Array.&lt;Object&gt;</span></span> | <span data-ttu-id="23147-797">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-797">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-798">Массив объектов JSON, представляющих собой вложенные файлы или элементы.</span><span class="sxs-lookup"><span data-stu-id="23147-798">An array of JSON objects that are either file or item attachments.</span></span> |
| `formData.attachments.type` | <span data-ttu-id="23147-799">String</span><span class="sxs-lookup"><span data-stu-id="23147-799">String</span></span> | | <span data-ttu-id="23147-p150">Указывает тип вложения. Допустимые значения: `file` для вложенного файла и `item` для вложенного элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-p150">Indicates the type of attachment. Must be `file` for a file attachment or `item` for an item attachment.</span></span> |
| `formData.attachments.name` | <span data-ttu-id="23147-802">String</span><span class="sxs-lookup"><span data-stu-id="23147-802">String</span></span> | | <span data-ttu-id="23147-803">Строка, содержащая имя вложения, длиной до 255 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-803">A string that contains the name of the attachment, up to 255 characters in length.</span></span>|
| `formData.attachments.url` | <span data-ttu-id="23147-804">String</span><span class="sxs-lookup"><span data-stu-id="23147-804">String</span></span> | | <span data-ttu-id="23147-p151">Используется, только если свойству `type` задано значение `file`. URI расположения файла.</span><span class="sxs-lookup"><span data-stu-id="23147-p151">Only used if `type` is set to `file`. The URI of the location for the file.</span></span> |
| `formData.attachments.isInline` | <span data-ttu-id="23147-807">Boolean</span><span class="sxs-lookup"><span data-stu-id="23147-807">Boolean</span></span> | | <span data-ttu-id="23147-p152">Используется, только если свойству `type` задано значение `file`. Значение `true` указывает на то, что вложение будет встроено в текст сообщения и не должно отображаться в списке вложений.</span><span class="sxs-lookup"><span data-stu-id="23147-p152">Only used if `type` is set to `file`. If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
| `formData.attachments.itemId` | <span data-ttu-id="23147-810">String</span><span class="sxs-lookup"><span data-stu-id="23147-810">String</span></span> | | <span data-ttu-id="23147-p153">Используется, только если свойству `type` задано значение `item`. Идентификатор вложения EWS. Это строка длиной до 100 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p153">Only used if `type` is set to `item`. The EWS item id of the attachment. This is a string up to 100 characters.</span></span> |
| `callback` | <span data-ttu-id="23147-814">function</span><span class="sxs-lookup"><span data-stu-id="23147-814">function</span></span> | <span data-ttu-id="23147-815">&lt;Необязательный&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-815">&lt;optional&gt;</span></span> | <span data-ttu-id="23147-816">По завершении работы метода функция, переданная параметру `callback`, вызывается с помощью одного параметра `asyncResult`, представляющего собой объект [AsyncResult](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-816">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [AsyncResult](/javascript/api/office/office.asyncresult) object.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-817">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-817">Requirements</span></span>

|<span data-ttu-id="23147-818">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-818">Requirement</span></span>| <span data-ttu-id="23147-819">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-819">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-820">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-820">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-821">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-821">1.0</span></span>|
|[<span data-ttu-id="23147-822">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-822">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-823">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-823">ReadItem</span></span>|
|[<span data-ttu-id="23147-824">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-824">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-825">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-825">Read</span></span>|

##### <a name="examples"></a><span data-ttu-id="23147-826">Примеры</span><span class="sxs-lookup"><span data-stu-id="23147-826">Examples</span></span>

<span data-ttu-id="23147-827">Приведенный ниже код передает строку в функцию `displayReplyForm`.</span><span class="sxs-lookup"><span data-stu-id="23147-827">The following code passes a string to the `displayReplyForm` function.</span></span>

```
Office.context.mailbox.item.displayReplyForm('hello there');
Office.context.mailbox.item.displayReplyForm('<b>hello there</b>');
```

<span data-ttu-id="23147-828">Ответ с пустым текстом сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-828">Reply with an empty body.</span></span>

```
Office.context.mailbox.item.displayReplyForm({});
```

<span data-ttu-id="23147-829">Ответ только с текстом сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-829">Reply with just a body.</span></span>

```
Office.context.mailbox.item.displayReplyForm(
{
  'htmlBody' : 'hi'
});
```

<span data-ttu-id="23147-830">Ответ с текстом сообщения и вложенным файлом.</span><span class="sxs-lookup"><span data-stu-id="23147-830">Reply with a body and a file attachment.</span></span>

```
Office.context.mailbox.item.displayReplyForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : Office.MailboxEnums.AttachmentType.File,
      'name' : 'squirrel.png',
      'url' : 'http://i.imgur.com/sRgTlGR.jpg'
    }
  ]
});
```

<span data-ttu-id="23147-831">Ответ с текстом сообщения и вложенным элементом.</span><span class="sxs-lookup"><span data-stu-id="23147-831">Reply with a body and an item attachment.</span></span>

```
Office.context.mailbox.item.displayReplyForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : 'item',
      'name' : 'rand',
      'itemId' : Office.context.mailbox.item.itemId
    }
  ]
});
```

<span data-ttu-id="23147-832">Ответ с текстом сообщения, вложенным файлом, вложенным элементом и обратным вызовом.</span><span class="sxs-lookup"><span data-stu-id="23147-832">Reply with a body, file attachment, item attachment, and a callback.</span></span>

```
Office.context.mailbox.item.displayReplyForm(
{
  'htmlBody' : 'hi',
  'attachments' :
  [
    {
      'type' : Office.MailboxEnums.AttachmentType.File,
      'name' : 'squirrel.png',
      'url' : 'http://i.imgur.com/sRgTlGR.jpg'
    },
    {
      'type' : 'item',
      'name' : 'rand',
      'itemId' : Office.context.mailbox.item.itemId
    }
  ],
  'callback' : function(asyncResult)
  {
    console.log(asyncResult.value);
  }
});
```

#### <a name="getentities--entitiesjavascriptapioutlook15officeentities"></a><span data-ttu-id="23147-833">getEntities() → {[Entities](/javascript/api/outlook_1_5/office.entities)}</span><span class="sxs-lookup"><span data-stu-id="23147-833">getEntities() → {[Entities](/javascript/api/outlook_1_5/office.entities)}</span></span>

<span data-ttu-id="23147-834">Возвращает сущности, обнаруженные в тело выбранного элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-834">Gets the entities found in the selected item's body.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-835">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-835">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-836">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-836">Requirements</span></span>

|<span data-ttu-id="23147-837">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-837">Requirement</span></span>| <span data-ttu-id="23147-838">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-838">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-839">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-839">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-840">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-840">1.0</span></span>|
|[<span data-ttu-id="23147-841">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-841">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-842">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-842">ReadItem</span></span>|
|[<span data-ttu-id="23147-843">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-843">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-844">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-844">Read</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-845">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-845">Returns:</span></span>

<span data-ttu-id="23147-846">Тип: [Entities](/javascript/api/outlook_1_5/office.entities)</span><span class="sxs-lookup"><span data-stu-id="23147-846">Type: [Entities](/javascript/api/outlook_1_5/office.entities)</span></span>

##### <a name="example"></a><span data-ttu-id="23147-847">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-847">Example</span></span>

<span data-ttu-id="23147-848">Этот пример ссылается сущностей контакты в тексте текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-848">The following example accesses the contacts entities in the current item's body.</span></span>

```
var contacts = Office.context.mailbox.item.getEntities().contacts;
```

#### <a name="getentitiesbytypeentitytype--nullable-arraystringcontactjavascriptapioutlook15officecontactmeetingsuggestionjavascriptapioutlook15officemeetingsuggestionphonenumberjavascriptapioutlook15officephonenumbertasksuggestionjavascriptapioutlook15officetasksuggestion"></a><span data-ttu-id="23147-849">getEntitiesByType(entityType) → (nullable) {Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))>}</span><span class="sxs-lookup"><span data-stu-id="23147-849">getEntitiesByType(entityType) → (nullable) {Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))>}</span></span>

<span data-ttu-id="23147-850">Получает массив всех сущностей указанного типа, обнаруженных в тело выбранного элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-850">Gets an array of all the entities of the specified entity type found in the selected item's body.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-851">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-851">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-852">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-852">Parameters:</span></span>

|<span data-ttu-id="23147-853">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-853">Name</span></span>| <span data-ttu-id="23147-854">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-854">Type</span></span>| <span data-ttu-id="23147-855">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-855">Description</span></span>|
|---|---|---|
|`entityType`| [<span data-ttu-id="23147-856">Office.MailboxEnums.EntityType</span><span class="sxs-lookup"><span data-stu-id="23147-856">Office.MailboxEnums.EntityType</span></span>](/javascript/api/outlook_1_5/office.mailboxenums.entitytype)|<span data-ttu-id="23147-857">Одно из значений перечисления EntityType.</span><span class="sxs-lookup"><span data-stu-id="23147-857">One of the EntityType enumeration values.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-858">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-858">Requirements</span></span>

|<span data-ttu-id="23147-859">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-859">Requirement</span></span>| <span data-ttu-id="23147-860">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-860">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-861">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-861">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-862">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-862">1.0</span></span>|
|[<span data-ttu-id="23147-863">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-863">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-864">Restricted</span><span class="sxs-lookup"><span data-stu-id="23147-864">Restricted</span></span>|
|[<span data-ttu-id="23147-865">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-865">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-866">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-866">Read</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-867">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-867">Returns:</span></span>

<span data-ttu-id="23147-868">Если значение, переданное в `entityType`, не является допустимым членом перечисления `EntityType`, метод возвращает значение NULL.</span><span class="sxs-lookup"><span data-stu-id="23147-868">If the value passed in `entityType` is not a valid member of the `EntityType` enumeration, the method returns null.</span></span> <span data-ttu-id="23147-869">Если сущности указанного типа отсутствуют в основной текст элемента, метод возвращает пустой массив.</span><span class="sxs-lookup"><span data-stu-id="23147-869">If no entities of the specified type are present in the item's body, the method returns an empty array.</span></span> <span data-ttu-id="23147-870">В противном случае тип объектов в возвращаемом массиве зависит от типа сущности, запрошенной в параметре `entityType`.</span><span class="sxs-lookup"><span data-stu-id="23147-870">Otherwise, the type of the objects in the returned array depends on the type of entity requested in the `entityType` parameter.</span></span>

<span data-ttu-id="23147-871">Хотя минимальный уровень разрешений для использования этого метода — **Restricted**, для некоторых типов сущностей требуется доступ на уровне **ReadItem**, как указано в приведенной ниже таблице.</span><span class="sxs-lookup"><span data-stu-id="23147-871">While the minimum permission level to use this method is **Restricted**, some entity types require **ReadItem** to access, as specified in the following table.</span></span>

| <span data-ttu-id="23147-872">Значение параметра `entityType`</span><span class="sxs-lookup"><span data-stu-id="23147-872">Value of `entityType`</span></span> | <span data-ttu-id="23147-873">Тип объектов в возвращаемом массиве</span><span class="sxs-lookup"><span data-stu-id="23147-873">Type of objects in returned array</span></span> | <span data-ttu-id="23147-874">Необходимый уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-874">Required Permission Level</span></span> |
| --- | --- | --- |
| `Address` | <span data-ttu-id="23147-875">String</span><span class="sxs-lookup"><span data-stu-id="23147-875">String</span></span> | <span data-ttu-id="23147-876">**Restricted**</span><span class="sxs-lookup"><span data-stu-id="23147-876">**Restricted**</span></span> |
| `Contact` | <span data-ttu-id="23147-877">Contact</span><span class="sxs-lookup"><span data-stu-id="23147-877">Contact</span></span> | <span data-ttu-id="23147-878">**ReadItem**</span><span class="sxs-lookup"><span data-stu-id="23147-878">**ReadItem**</span></span> |
| `EmailAddress` | <span data-ttu-id="23147-879">String</span><span class="sxs-lookup"><span data-stu-id="23147-879">String</span></span> | <span data-ttu-id="23147-880">**ReadItem**</span><span class="sxs-lookup"><span data-stu-id="23147-880">**ReadItem**</span></span> |
| `MeetingSuggestion` | <span data-ttu-id="23147-881">MeetingSuggestion</span><span class="sxs-lookup"><span data-stu-id="23147-881">MeetingSuggestion</span></span> | <span data-ttu-id="23147-882">**ReadItem**</span><span class="sxs-lookup"><span data-stu-id="23147-882">**ReadItem**</span></span> |
| `PhoneNumber` | <span data-ttu-id="23147-883">PhoneNumber</span><span class="sxs-lookup"><span data-stu-id="23147-883">PhoneNumber</span></span> | <span data-ttu-id="23147-884">**Restricted**</span><span class="sxs-lookup"><span data-stu-id="23147-884">**Restricted**</span></span> |
| `TaskSuggestion` | <span data-ttu-id="23147-885">TaskSuggestion</span><span class="sxs-lookup"><span data-stu-id="23147-885">TaskSuggestion</span></span> | <span data-ttu-id="23147-886">**ReadItem**</span><span class="sxs-lookup"><span data-stu-id="23147-886">**ReadItem**</span></span> |
| `URL` | <span data-ttu-id="23147-887">String</span><span class="sxs-lookup"><span data-stu-id="23147-887">String</span></span> | <span data-ttu-id="23147-888">**Restricted**</span><span class="sxs-lookup"><span data-stu-id="23147-888">**Restricted**</span></span> |

<span data-ttu-id="23147-889">Тип: Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))></span><span class="sxs-lookup"><span data-stu-id="23147-889">Type: Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))></span></span>

##### <a name="example"></a><span data-ttu-id="23147-890">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-890">Example</span></span>

<span data-ttu-id="23147-891">Следующем примере показано, как получить доступ к массив строк, представляющих почтовых адресов в тексте текущего элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-891">The following example shows how to access an array of strings that represent postal addresses in the current item's body.</span></span>

```
// The initialize function is required for all apps.
Office.initialize = function () {
  // Checks for the DOM to load using the jQuery ready function.
  $(document).ready(function () {
    // After the DOM is loaded, app-specific code can run.
    var item = Office.context.mailbox.item;
    // Get an array of strings that represent postal addresses in the current item's body.
    var addresses = item.getEntitiesByType(Office.MailboxEnums.EntityType.Address);
    // Continue processing the array of addresses.
  });
}
```

#### <a name="getfilteredentitiesbynamename--nullable-arraystringcontactjavascriptapioutlook15officecontactmeetingsuggestionjavascriptapioutlook15officemeetingsuggestionphonenumberjavascriptapioutlook15officephonenumbertasksuggestionjavascriptapioutlook15officetasksuggestion"></a><span data-ttu-id="23147-892">getFilteredEntitiesByName(name) → (nullable) {Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))>}</span><span class="sxs-lookup"><span data-stu-id="23147-892">getFilteredEntitiesByName(name) → (nullable) {Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))>}</span></span>

<span data-ttu-id="23147-893">Возвращает известные сущности в выбранном элементе, которые проходят через именованный фильтр, определяемый в XML-файле манифеста.</span><span class="sxs-lookup"><span data-stu-id="23147-893">Returns well-known entities in the selected item that pass the named filter defined in the manifest XML file.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-894">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-894">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="23147-895">Метод `getFilteredEntitiesByName` возвращает сущности, соответствующие регулярному выражению, которое определяется в элементе правила [ItemHasKnownEntity](/javascript/office/manifest/rule#itemhasknownentity-rule) в XML-файле манифеста, с использованием указанного значения элемента `FilterName`.</span><span class="sxs-lookup"><span data-stu-id="23147-895">The `getFilteredEntitiesByName` method returns the entities that match the regular expression defined in the [ItemHasKnownEntity](/javascript/office/manifest/rule#itemhasknownentity-rule) rule element in the manifest XML file with the specified `FilterName` element value.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-896">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-896">Parameters:</span></span>

|<span data-ttu-id="23147-897">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-897">Name</span></span>| <span data-ttu-id="23147-898">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-898">Type</span></span>| <span data-ttu-id="23147-899">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-899">Description</span></span>|
|---|---|---|
|`name`| <span data-ttu-id="23147-900">String</span><span class="sxs-lookup"><span data-stu-id="23147-900">String</span></span>|<span data-ttu-id="23147-901">Имя элемента правила `ItemHasKnownEntity`, определяющее соответствующий фильтр.</span><span class="sxs-lookup"><span data-stu-id="23147-901">The name of the `ItemHasKnownEntity` rule element that defines the filter to match.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-902">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-902">Requirements</span></span>

|<span data-ttu-id="23147-903">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-903">Requirement</span></span>| <span data-ttu-id="23147-904">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-904">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-905">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-905">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-906">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-906">1.0</span></span>|
|[<span data-ttu-id="23147-907">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-907">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-908">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-908">ReadItem</span></span>|
|[<span data-ttu-id="23147-909">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-909">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-910">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-910">Read</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-911">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-911">Returns:</span></span>

<span data-ttu-id="23147-p155">Если в манифесте нет элемента `ItemHasKnownEntity` со значением `FilterName`, соответствующим параметру `name`, метод возвращает `null`. Если параметр `name` соответствует элементу `ItemHasKnownEntity` в манифесте, но при этом в текущем элементе нет соответствующих сущностей, метод возвращает пустой массив.</span><span class="sxs-lookup"><span data-stu-id="23147-p155">If there is no `ItemHasKnownEntity` element in the manifest with a `FilterName` element value that matches the `name` parameter, the method returns `null`. If the `name` parameter does match an `ItemHasKnownEntity` element in the manifest, but there are no entities in the current item that match, the method return an empty array.</span></span>

<span data-ttu-id="23147-914">Тип: Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))></span><span class="sxs-lookup"><span data-stu-id="23147-914">Type: Array.<(String|[Contact](/javascript/api/outlook_1_5/office.contact)|[MeetingSuggestion](/javascript/api/outlook_1_5/office.meetingsuggestion)|[PhoneNumber](/javascript/api/outlook_1_5/office.phonenumber)|[TaskSuggestion](/javascript/api/outlook_1_5/office.tasksuggestion))></span></span>

#### <a name="getregexmatches--object"></a><span data-ttu-id="23147-915">getRegExMatches() → {Object}</span><span class="sxs-lookup"><span data-stu-id="23147-915">getRegExMatches() → {Object}</span></span>

<span data-ttu-id="23147-916">Возвращает строковые значения в выбранном элементе, которые соответствуют регулярным выражениям, определенным в XML-файле манифеста.</span><span class="sxs-lookup"><span data-stu-id="23147-916">Returns string values in the selected item that match the regular expressions defined in the manifest XML file.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-917">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-917">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="23147-p156">Метод `getRegExMatches` возвращает строки, соответствующие регулярному выражению, которое определяется в каждом элементе правила `ItemHasRegularExpressionMatch` или `ItemHasKnownEntity` в XML-файле манифеста. Для правила `ItemHasRegularExpressionMatch` соответствующую строку должно содержать свойство элемента, указанного этим правилом. Простой тип `PropertyName` определяет поддерживаемые свойства.</span><span class="sxs-lookup"><span data-stu-id="23147-p156">The `getRegExMatches` method returns the strings that match the regular expression defined in each `ItemHasRegularExpressionMatch` or `ItemHasKnownEntity` rule element in the manifest XML file. For an `ItemHasRegularExpressionMatch` rule, a matching string has to occur in the property of the item that is specified by that rule. The `PropertyName` simple type defines the supported properties.</span></span>

<span data-ttu-id="23147-921">Например, рассмотрим манифест надстройки, который содержит указанный ниже элемент `Rule`.</span><span class="sxs-lookup"><span data-stu-id="23147-921">For example, consider an add-in manifest has the following `Rule` element:</span></span>

```
<Rule xsi:type="RuleCollection" Mode="And">
  <Rule xsi:type="ItemIs" FormType="Read" ItemType="Message" />
  <Rule xsi:type="RuleCollection" Mode="Or">
    <Rule xsi:type="ItemHasRegularExpressionMatch" RegExName="fruits" RegExValue="apple|banana|coconut" PropertyName="BodyAsPlaintext" IgnoreCase="true" />
    <Rule xsi:type="ItemHasRegularExpressionMatch" RegExName="veggies" RegExValue="tomato|onion|spinach|broccoli" PropertyName="BodyAsPlaintext" IgnoreCase="true" />
  </Rule>
</Rule>
```

<span data-ttu-id="23147-922">Объект, возвращаемый методом `getRegExMatches`, будет содержать два свойства: `fruits` и `veggies`.</span><span class="sxs-lookup"><span data-stu-id="23147-922">The object returned from `getRegExMatches` would have two properties: `fruits` and `veggies`.</span></span>

```
{
  'fruits': ['apple','banana','Banana','coconut'],
  'veggies': ['tomato','onion','spinach','broccoli']
}
```

<span data-ttu-id="23147-p157">Если вы указываете правило `ItemHasRegularExpressionMatch` для свойства текста элемента, регулярное выражение должно дальше фильтровать текст, а не пытаться вернуть весь текст элемента. Использование регулярного выражения, такого как `.*`, для получения всего текста элемента не всегда приносит ожидаемые результаты. Лучше используйте метод [`Body.getAsync`](/javascript/api/outlook_1_5/office.body#getasync-coerciontype--options--callback-) для этого.</span><span class="sxs-lookup"><span data-stu-id="23147-p157">If you specify an `ItemHasRegularExpressionMatch` rule on the body property of an item, the regular expression should further filter the body and should not attempt to return the entire body of the item. Using a regular expression such as `.*` to obtain the entire body of an item does not always return the expected results. Instead, use the [`Body.getAsync`](/javascript/api/outlook_1_5/office.body#getasync-coerciontype--options--callback-) method to retrieve the entire body.</span></span>

##### <a name="requirements"></a><span data-ttu-id="23147-926">Requirements</span><span class="sxs-lookup"><span data-stu-id="23147-926">Requirements</span></span>

|<span data-ttu-id="23147-927">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-927">Requirement</span></span>| <span data-ttu-id="23147-928">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-928">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-929">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-929">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-930">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-930">1.0</span></span>|
|[<span data-ttu-id="23147-931">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-931">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-932">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-932">ReadItem</span></span>|
|[<span data-ttu-id="23147-933">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-933">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-934">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-934">Read</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-935">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-935">Returns:</span></span>

<span data-ttu-id="23147-p158">Объект, содержащий массив строк, которые соответствуют регулярным выражениям, определяемым в XML-файле манифеста. Имя каждого массива равно соответствующему значению атрибута `RegExName` подходящего правила `ItemHasRegularExpressionMatch` или атрибута `FilterName` соответствующего правила `ItemHasKnownEntity`.</span><span class="sxs-lookup"><span data-stu-id="23147-p158">An object that contains arrays of strings that match the regular expressions defined in the manifest XML file. The name of each array is equal to the corresponding value of the `RegExName` attribute of the matching `ItemHasRegularExpressionMatch` rule or the `FilterName` attribute of the matching `ItemHasKnownEntity` rule.</span></span>

<dl class="param-type"><span data-ttu-id="23147-938">

<dt>Тип</dt>

</span><span class="sxs-lookup"><span data-stu-id="23147-938">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="23147-939">Object</span><span class="sxs-lookup"><span data-stu-id="23147-939">Object</span></span></dd>

</dl>

##### <a name="example"></a><span data-ttu-id="23147-940">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-940">Example</span></span>

<span data-ttu-id="23147-941">В примере ниже показано, как получить доступ к массиву совпадений для элементов <rule> регулярного выражения `fruits` и `veggies`, которые указаны в манифесте.</rule></span><span class="sxs-lookup"><span data-stu-id="23147-941">The following example shows how to access the array of matches for the regular expression <rule>elements `fruits` and `veggies`, which are specified in the manifest.</rule></span></span>

```
var allMatches = Office.context.mailbox.item.getRegExMatches();
var fruits = allMatches.fruits;
var veges = allMatches.veggies;
```

#### <a name="getregexmatchesbynamename--nullable-array-string-"></a><span data-ttu-id="23147-942">getRegExMatchesByName(name) пункты (допускает значение NULL) {массива. < String >}</span><span class="sxs-lookup"><span data-stu-id="23147-942">getRegExMatchesByName(name) → (nullable) {Array.< String >}</span></span>

<span data-ttu-id="23147-943">Возвращает строковые значения в выбранном элементе, которые соответствуют именованному регулярному выражению, определенному в XML-файле манифеста.</span><span class="sxs-lookup"><span data-stu-id="23147-943">Returns string values in the selected item that match the named regular expression defined in the manifest XML file.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-944">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="23147-944">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="23147-945">Метод `getRegExMatchesByName` возвращает строки, соответствующие регулярному выражению, которое определяется в элементе правила `ItemHasRegularExpressionMatch` в XML-файле манифеста, с использованием указанного значения элемента `RegExName`.</span><span class="sxs-lookup"><span data-stu-id="23147-945">The `getRegExMatchesByName` method returns the strings that match the regular expression defined in the `ItemHasRegularExpressionMatch` rule element in the manifest XML file with the specified `RegExName` element value.</span></span>

<span data-ttu-id="23147-p159">Если вы указываете правило `ItemHasRegularExpressionMatch` для свойства текста элемента, регулярное выражение должно дальше фильтровать текст, а не пытаться вернуть весь текст элемента. Использование регулярного выражения, такого как `.*`, для получения всего текста элемента не всегда приносит ожидаемые результаты.</span><span class="sxs-lookup"><span data-stu-id="23147-p159">If you specify an `ItemHasRegularExpressionMatch` rule on the body property of an item, the regular expression should further filter the body and should not attempt to return the entire body of the item. Using a regular expression such as `.*` to obtain the entire body of an item does not always return the expected results.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-948">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-948">Parameters:</span></span>

|<span data-ttu-id="23147-949">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-949">Name</span></span>| <span data-ttu-id="23147-950">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-950">Type</span></span>| <span data-ttu-id="23147-951">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-951">Description</span></span>|
|---|---|---|
|`name`| <span data-ttu-id="23147-952">String</span><span class="sxs-lookup"><span data-stu-id="23147-952">String</span></span>|<span data-ttu-id="23147-953">Имя элемента правила `ItemHasRegularExpressionMatch`, определяющее соответствующий фильтр.</span><span class="sxs-lookup"><span data-stu-id="23147-953">The name of the `ItemHasRegularExpressionMatch` rule element that defines the filter to match.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-954">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-954">Requirements</span></span>

|<span data-ttu-id="23147-955">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-955">Requirement</span></span>| <span data-ttu-id="23147-956">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-956">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-957">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-957">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-958">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-958">1.0</span></span>|
|[<span data-ttu-id="23147-959">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-959">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-960">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-960">ReadItem</span></span>|
|[<span data-ttu-id="23147-961">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-961">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-962">Чтение</span><span class="sxs-lookup"><span data-stu-id="23147-962">Read</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-963">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-963">Returns:</span></span>

<span data-ttu-id="23147-964">Массив строк, соответствующих регулярному выражению, определяемому в XML-файле манифеста.</span><span class="sxs-lookup"><span data-stu-id="23147-964">An array that contains the strings that match the regular expression defined in the manifest XML file.</span></span>

<dl class="param-type"><span data-ttu-id="23147-965">

<dt>Тип</dt>

</span><span class="sxs-lookup"><span data-stu-id="23147-965">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="23147-966">Массив. < String ></span><span class="sxs-lookup"><span data-stu-id="23147-966">Array.< String ></span></span></dd>

</dl>

##### <a name="example"></a><span data-ttu-id="23147-967">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-967">Example</span></span>

```
var fruits = Office.context.mailbox.item.getRegExMatchesByName("fruits");
var veggies = Office.context.mailbox.item.getRegExMatchesByName("veggies");
```

####  <a name="getselecteddataasynccoerciontype-options-callback--string"></a><span data-ttu-id="23147-968">getSelectedDataAsync(coercionType, [options], callback) → {String}</span><span class="sxs-lookup"><span data-stu-id="23147-968">getSelectedDataAsync(coercionType, [options], callback) → {String}</span></span>

<span data-ttu-id="23147-969">Асинхронно возвращает данные, выбранные в теме или тексте сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-969">Asynchronously returns selected data from the subject or body of a message.</span></span>

<span data-ttu-id="23147-p160">Если выделенный фрагмент отсутствует, но курсор находится в тексте или теме, метод возвращает значение NULL для выбранных данных. Если выбраны не текст и не тема, метод возвращает ошибку `InvalidSelection`.</span><span class="sxs-lookup"><span data-stu-id="23147-p160">If there is no selection but the cursor is in the body or subject, the method returns null for the selected data. If a field other than the body or subject is selected, the method returns the `InvalidSelection` error.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-972">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-972">Parameters:</span></span>

|<span data-ttu-id="23147-973">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-973">Name</span></span>| <span data-ttu-id="23147-974">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-974">Type</span></span>| <span data-ttu-id="23147-975">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-975">Attributes</span></span>| <span data-ttu-id="23147-976">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-976">Description</span></span>|
|---|---|---|---|
|`coercionType`| [<span data-ttu-id="23147-977">Office.CoercionType</span><span class="sxs-lookup"><span data-stu-id="23147-977">Office.CoercionType</span></span>](office.md#coerciontype-string)||<span data-ttu-id="23147-p161">Запрашивает формат данных. Если задано значение Text, метод возвращает обычный текст как строку, удаляя все имеющиеся HTML-теги. Если задано значение HTML, метод возвращает выделенный текст (обычный текст или HTML).</span><span class="sxs-lookup"><span data-stu-id="23147-p161">Requests a format for the data. If Text, the method returns the plain text as a string , removing any HTML tags present. If HTML, the method returns the selected text, whether it is plaintext or HTML.</span></span>|
|`options`| <span data-ttu-id="23147-981">Object</span><span class="sxs-lookup"><span data-stu-id="23147-981">Object</span></span>| <span data-ttu-id="23147-982">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-982">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-983">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-983">An object literal that contains one or more of the following properties.</span></span>|
|`options.asyncContext`| <span data-ttu-id="23147-984">Object</span><span class="sxs-lookup"><span data-stu-id="23147-984">Object</span></span>| <span data-ttu-id="23147-985">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-985">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-986">Разработчики могут указать любой объект, к которому необходимо получить доступ, в методе обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-986">Developers can provide any object they wish to access in the callback method.</span></span>|
|`callback`| <span data-ttu-id="23147-987">function</span><span class="sxs-lookup"><span data-stu-id="23147-987">function</span></span>||<span data-ttu-id="23147-988">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-988">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="23147-989">Чтобы получить доступ к выбранным данным из метода обратного вызова, вызовите `asyncResult.value.data`.</span><span class="sxs-lookup"><span data-stu-id="23147-989">To access the selected data from the callback method, call `asyncResult.value.data`.</span></span> <span data-ttu-id="23147-990">Для доступа к свойству источника, выделение, поступающих из источников, вызовите `asyncResult.value.sourceProperty`, который может быть либо `body` или `subject`.</span><span class="sxs-lookup"><span data-stu-id="23147-990">To access the source property that the selection comes from, call `asyncResult.value.sourceProperty`, which will be either `body` or `subject`.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-991">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-991">Requirements</span></span>

|<span data-ttu-id="23147-992">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-992">Requirement</span></span>| <span data-ttu-id="23147-993">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-993">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-994">Минимальная версия набора обязательных элементов для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="23147-994">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-995">1.2</span><span class="sxs-lookup"><span data-stu-id="23147-995">1.2</span></span>|
|[<span data-ttu-id="23147-996">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-996">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-997">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-997">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-998">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-998">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-999">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-999">Compose</span></span>|

##### <a name="returns"></a><span data-ttu-id="23147-1000">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="23147-1000">Returns:</span></span>

<span data-ttu-id="23147-1001">Выбранные данные в виде строки с форматом, определенным в параметре `coercionType`.</span><span class="sxs-lookup"><span data-stu-id="23147-1001">The selected data as a string with format determined by `coercionType`.</span></span>

<dl class="param-type"><span data-ttu-id="23147-1002">

<dt>Тип</dt>

</span><span class="sxs-lookup"><span data-stu-id="23147-1002">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="23147-1003">String</span><span class="sxs-lookup"><span data-stu-id="23147-1003">String</span></span></dd>

</dl>

##### <a name="example"></a><span data-ttu-id="23147-1004">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-1004">Example</span></span>

```
// getting selected data
Office.initialize = function () {
    Office.context.mailbox.item.getSelectedDataAsync(Office.CoercionType.Text, {}, getCallback);
}

function getCallback(asyncResult) {
    var text = asyncResult.value.data;
    var prop = asyncResult.value.sourceProperty;

    Office.context.mailbox.item.setSelectedDataAsync('Setting ' + prop + ': ' + text, {}, setCallback);
}

function setCallback(asyncResult) {
    // check for errors
}
```

####  <a name="loadcustompropertiesasynccallback-usercontext"></a><span data-ttu-id="23147-1005">loadCustomPropertiesAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="23147-1005">loadCustomPropertiesAsync(callback, [userContext])</span></span>

<span data-ttu-id="23147-1006">Асинхронно загружает настраиваемые свойства для надстройки для выбранного элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-1006">Asynchronously loads custom properties for this add-in on the selected item.</span></span>

<span data-ttu-id="23147-p163">Настраиваемые свойства сохраняются в виде пар "ключ-значение" для каждого приложения и каждого элемента. Этот метод возвращает объект `CustomProperties` при обратном вызове, который предоставляет методы для доступа к настраиваемым свойствам, характерным для текущего элемента и текущей надстройки. Настраиваемые свойства не шифруются для элемента, поэтому этот способ хранения не является безопасным.</span><span class="sxs-lookup"><span data-stu-id="23147-p163">Custom properties are stored as key/value pairs on a per-app, per-item basis. This method returns a `CustomProperties` object in the callback, which provides methods to access the custom properties specific to the current item and the current add-in. Custom properties are not encrypted on the item, so this should not be used as secure storage.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-1010">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-1010">Parameters:</span></span>

|<span data-ttu-id="23147-1011">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-1011">Name</span></span>| <span data-ttu-id="23147-1012">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-1012">Type</span></span>| <span data-ttu-id="23147-1013">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-1013">Attributes</span></span>| <span data-ttu-id="23147-1014">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-1014">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="23147-1015">function</span><span class="sxs-lookup"><span data-stu-id="23147-1015">function</span></span>||<span data-ttu-id="23147-1016">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-1016">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="23147-1017">Настраиваемые свойства предоставляются в виде объекта [`CustomProperties`](/javascript/api/outlook_1_5/office.customproperties) в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="23147-1017">The custom properties are provided as a [`CustomProperties`](/javascript/api/outlook_1_5/office.customproperties) object in the `asyncResult.value` property.</span></span> <span data-ttu-id="23147-1018">Этот объект можно использовать для получения, задания и удаление настраиваемых свойств из элемента и сохранение изменений для настраиваемого свойства, задайте обратно на сервер.</span><span class="sxs-lookup"><span data-stu-id="23147-1018">This object can be used to get, set, and remove custom properties from the item and save changes to the custom property set back to the server.</span></span>|
|`userContext`| <span data-ttu-id="23147-1019">Объект</span><span class="sxs-lookup"><span data-stu-id="23147-1019">Object</span></span>| <span data-ttu-id="23147-1020">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1020">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1021">Разработчики могут предоставлять любого объекта, которые следует получить доступ к в функции обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-1021">Developers can provide any object they wish to access in the callback function.</span></span> <span data-ttu-id="23147-1022">Этот объект можно получить доступ с `asyncResult.asyncContext` в функции обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-1022">This object can be accessed by the `asyncResult.asyncContext` property in the callback function.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-1023">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-1023">Requirements</span></span>

|<span data-ttu-id="23147-1024">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-1024">Requirement</span></span>| <span data-ttu-id="23147-1025">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-1025">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-1026">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-1026">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-1027">1.0</span><span class="sxs-lookup"><span data-stu-id="23147-1027">1.0</span></span>|
|[<span data-ttu-id="23147-1028">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-1028">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-1029">ReadItem</span><span class="sxs-lookup"><span data-stu-id="23147-1029">ReadItem</span></span>|
|[<span data-ttu-id="23147-1030">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-1030">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-1031">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="23147-1031">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-1032">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-1032">Example</span></span>

<span data-ttu-id="23147-p166">Приведенный ниже пример кода показывает, как асинхронно загружать настраиваемые свойства, характерные для текущего элемента, с помощью метода `loadCustomPropertiesAsync`. Этот пример также показывает, как сохранять эти свойства на сервере с помощью метода `CustomProperties.saveAsync`. После загрузки настраиваемых свойств в этом примере кода метод `CustomProperties.get` используется для считывания настраиваемого свойства `myProp`, метод `CustomProperties.set` — для записи настраиваемого свойства `otherProp`, а метод `saveAsync` — для сохранения настраиваемых свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-p166">The following code example shows how to use the `loadCustomPropertiesAsync` method to asynchronously load custom properties that are specific to the current item. The example also shows how to use the `CustomProperties.saveAsync` method to save these properties back to the server. After loading the custom properties, the code sample uses the `CustomProperties.get` method to read the custom property `myProp`, the `CustomProperties.set` method to write the custom property `otherProp`, and then finally calls the `saveAsync` method to save the custom properties.</span></span>

```
// The initialize function is required for all add-ins.
Office.initialize = function () {
  // Checks for the DOM to load using the jQuery ready function.
  $(document).ready(function () {
  // After the DOM is loaded, add-in-specific code can run.
  var item = Office.context.mailbox.item;
  item.loadCustomPropertiesAsync(customPropsCallback);
  });
}

function customPropsCallback(asyncResult) {
  var customProps = asyncResult.value;
  var myProp = customProps.get("myProp");

  customProps.set("otherProp", "value");
  customProps.saveAsync(saveCallback);
}

function saveCallback(asyncResult) {
}
```

####  <a name="removeattachmentasyncattachmentid-options-callback"></a><span data-ttu-id="23147-1036">removeAttachmentAsync(attachmentId, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="23147-1036">removeAttachmentAsync(attachmentId, [options], [callback])</span></span>

<span data-ttu-id="23147-1037">Удаляет вложение из сообщения или встречи.</span><span class="sxs-lookup"><span data-stu-id="23147-1037">Removes an attachment from a message or appointment.</span></span>

<span data-ttu-id="23147-p167">Метод `removeAttachmentAsync` удаляет из элемента вложение с указанным идентификатором. Идентификатор вложения рекомендуется использовать для удаления вложения, только если оно добавлено тем же почтовым приложением в ходе текущего сеанса. В Outlook Web App и Outlook Web App для устройств идентификатор вложения действителен только в рамках одного сеанса. Сеанс завершается, когда пользователь закрывает приложение или начинает создавать элемент во встроенной форме, а затем переходит из формы в отдельное окно.</span><span class="sxs-lookup"><span data-stu-id="23147-p167">The `removeAttachmentAsync` method removes the attachment with the specified identifier from the item. As a best practice, you should use the attachment identifier to remove an attachment only if the same mail app has added that attachment in the same session. In Outlook Web App and OWA for Devices, the attachment identifier is valid only within the same session. A session is over when the user closes the app, or if the user starts composing in an inline form and subsequently pops out the inline form to continue in a separate window.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-1042">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-1042">Parameters:</span></span>

|<span data-ttu-id="23147-1043">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-1043">Name</span></span>| <span data-ttu-id="23147-1044">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-1044">Type</span></span>| <span data-ttu-id="23147-1045">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-1045">Attributes</span></span>| <span data-ttu-id="23147-1046">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-1046">Description</span></span>|
|---|---|---|---|
|`attachmentId`| <span data-ttu-id="23147-1047">String</span><span class="sxs-lookup"><span data-stu-id="23147-1047">String</span></span>||<span data-ttu-id="23147-p168">Идентификатор удаляемого вложения. Максимальная длина строки — 100 символов.</span><span class="sxs-lookup"><span data-stu-id="23147-p168">The identifier of the attachment to remove. The maximum length of the string is 100 characters.</span></span>|
|`options`| <span data-ttu-id="23147-1050">Object</span><span class="sxs-lookup"><span data-stu-id="23147-1050">Object</span></span>| <span data-ttu-id="23147-1051">&lt;необязательный&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1051">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1052">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-1052">An object literal that contains one or more of the following properties.</span></span>|
|`options.asyncContext`| <span data-ttu-id="23147-1053">Object</span><span class="sxs-lookup"><span data-stu-id="23147-1053">Object</span></span>| <span data-ttu-id="23147-1054">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1054">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1055">Разработчики могут указать любой объект, к которому необходимо получить доступ, в методе обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-1055">Developers can provide any object they wish to access in the callback method.</span></span>|
|`callback`| <span data-ttu-id="23147-1056">function</span><span class="sxs-lookup"><span data-stu-id="23147-1056">function</span></span>| <span data-ttu-id="23147-1057">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1057">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1058">После выполнения метода функция, переданная в параметре `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-1058">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span> <br/><span data-ttu-id="23147-1059">Если удалить вложение не удается, свойство `asyncResult.error` содержит код ошибки с указанием ее причины.</span><span class="sxs-lookup"><span data-stu-id="23147-1059">If removing the attachment fails, the `asyncResult.error` property will contain an error code with the reason for the failure.</span></span>|

##### <a name="errors"></a><span data-ttu-id="23147-1060">Ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-1060">Errors</span></span>

| <span data-ttu-id="23147-1061">Код ошибки</span><span class="sxs-lookup"><span data-stu-id="23147-1061">Error code</span></span> | <span data-ttu-id="23147-1062">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-1062">Description</span></span> |
|------------|-------------|
| `InvalidAttachmentId` | <span data-ttu-id="23147-1063">Идентификатор вложения не существует.</span><span class="sxs-lookup"><span data-stu-id="23147-1063">The attachment identifier does not exist.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-1064">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-1064">Requirements</span></span>

|<span data-ttu-id="23147-1065">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-1065">Requirement</span></span>| <span data-ttu-id="23147-1066">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-1066">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-1067">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-1067">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-1068">1.1</span><span class="sxs-lookup"><span data-stu-id="23147-1068">1.1</span></span>|
|[<span data-ttu-id="23147-1069">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-1069">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-1070">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-1070">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-1071">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-1071">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-1072">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-1072">Compose</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-1073">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-1073">Example</span></span>

<span data-ttu-id="23147-1074">Указанный ниже код удаляет вложение с идентификатором "0".</span><span class="sxs-lookup"><span data-stu-id="23147-1074">The following code removes an attachment with an identifier of '0'.</span></span>

```
Office.context.mailbox.item.removeAttachmentAsync(
  '0',
  { asyncContext : null },
  function (asyncResult)
  {
    console.log(asyncResult.status);
  }
);
```

####  <a name="saveasyncoptions-callback"></a><span data-ttu-id="23147-1075">saveAsync([options], callback)</span><span class="sxs-lookup"><span data-stu-id="23147-1075">saveAsync([options], callback)</span></span>

<span data-ttu-id="23147-1076">Асинхронно сохраняет элемент.</span><span class="sxs-lookup"><span data-stu-id="23147-1076">Asynchronously saves an item.</span></span>

<span data-ttu-id="23147-p169">При вызове этот метод сохраняет текущее сообщение в виде черновика и возвращает идентификатор элемента с помощью метода обратного вызова. В Outlook Web App или интерактивном режиме Outlook этот элемент сохраняется на сервере. В Outlook в режиме кэширования этот элемент сохраняется в локальном кэше.</span><span class="sxs-lookup"><span data-stu-id="23147-p169">When invoked, this method saves the current message as a draft and returns the item id via the callback method. In Outlook Web App or Outlook in online mode, the item is saved to the server. In Outlook in cached mode, the item is saved to the local cache.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-1080">Если надстройка вызывает `saveAsync` элемент в режиме создания для получения `itemId` для использования с помощью веб-служб Exchange или интерфейса API REST, необходимо учитывать, что когда Outlook находится в режиме кэширования, он может занять некоторое время до элемента фактически синхронизируется с сервера.</span><span class="sxs-lookup"><span data-stu-id="23147-1080">If your add-in calls `saveAsync` on an item in compose mode in order to get an `itemId` to use with EWS or the REST API, be aware that when Outlook is in cached mode, it may take some time before the item is actually synced to the server.</span></span> <span data-ttu-id="23147-1081">Пока элемент синхронизирован с помощью `itemId` возвращает ошибку.</span><span class="sxs-lookup"><span data-stu-id="23147-1081">Until the item is synced, using the `itemId` will return an error.</span></span>

<span data-ttu-id="23147-p171">Если метод `saveAsync` вызывается для встречи в режиме создания, она сохраняется как обычная встреча в календаре пользователя, а не как черновик. При сохранении новой встречи приглашения не отправляются. При сохранении существующей встречи уведомления отправляются добавленным или удаленным участникам.</span><span class="sxs-lookup"><span data-stu-id="23147-p171">Since appointments have no draft state, if `saveAsync` is called on an appointment in compose mode, the item will be saved as a normal appointment on the user's calendar. For new appointments that have not been saved before, no invitation will be sent. Saving an existing appointment will send an update to added or removed attendees.</span></span>

> [!NOTE]
> <span data-ttu-id="23147-1085">Следующие клиенты имеют по-разному для `saveAsync` для встреч в режиме создания:</span><span class="sxs-lookup"><span data-stu-id="23147-1085">The following clients have different behavior for `saveAsync` on appointments in compose mode:</span></span>
>
> - <span data-ttu-id="23147-1086">Mac Outlook не поддерживает `saveAsync` на собрании в режиме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-1086">Mac Outlook does not support `saveAsync` on a meeting in compose mode.</span></span> <span data-ttu-id="23147-1087">Вызов `saveAsync` собрания в Mac Outlook возвращает ошибку.</span><span class="sxs-lookup"><span data-stu-id="23147-1087">Calling `saveAsync` on a meeting in Mac Outlook will return an error.</span></span>
> - <span data-ttu-id="23147-1088">Outlook в Интернете всегда отправляет приглашение или обновления при `saveAsync` вызван на встречи в режиме создания.</span><span class="sxs-lookup"><span data-stu-id="23147-1088">Outlook on the web always sends an invitation or update when `saveAsync` is called on an appointment in compose mode.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-1089">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-1089">Parameters:</span></span>

|<span data-ttu-id="23147-1090">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-1090">Name</span></span>| <span data-ttu-id="23147-1091">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-1091">Type</span></span>| <span data-ttu-id="23147-1092">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-1092">Attributes</span></span>| <span data-ttu-id="23147-1093">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-1093">Description</span></span>|
|---|---|---|---|
|`options`| <span data-ttu-id="23147-1094">Объект</span><span class="sxs-lookup"><span data-stu-id="23147-1094">Object</span></span>| <span data-ttu-id="23147-1095">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1095">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1096">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-1096">An object literal that contains one or more of the following properties.</span></span>|
|`options.asyncContext`| <span data-ttu-id="23147-1097">Object</span><span class="sxs-lookup"><span data-stu-id="23147-1097">Object</span></span>| <span data-ttu-id="23147-1098">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1098">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1099">Разработчики могут указать любой объект, к которому необходимо получить доступ, в методе обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="23147-1099">Developers can provide any object they wish to access in the callback method.</span></span>|
|`callback`| <span data-ttu-id="23147-1100">function</span><span class="sxs-lookup"><span data-stu-id="23147-1100">function</span></span>||<span data-ttu-id="23147-1101">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-1101">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="23147-1102">В случае успешного выполнения, идентификатор элемента представлен в `asyncResult.value` свойство.</span><span class="sxs-lookup"><span data-stu-id="23147-1102">On success, the item identifier is provided in the `asyncResult.value` property.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="23147-1103">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-1103">Requirements</span></span>

|<span data-ttu-id="23147-1104">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-1104">Requirement</span></span>| <span data-ttu-id="23147-1105">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-1105">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-1106">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="23147-1106">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-1107">1.3</span><span class="sxs-lookup"><span data-stu-id="23147-1107">1.3</span></span>|
|[<span data-ttu-id="23147-1108">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-1108">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-1109">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-1109">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-1110">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-1110">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-1111">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-1111">Compose</span></span>|

##### <a name="examples"></a><span data-ttu-id="23147-1112">Примеры</span><span class="sxs-lookup"><span data-stu-id="23147-1112">Examples</span></span>

```
Office.context.mailbox.item.saveAsync(
  function callback(result) {
    // Process the result
  });
```

<span data-ttu-id="23147-p173">Ниже приведен пример параметра `result`, переданного функции обратного вызова. Свойство `value` содержит идентификатор элемента.</span><span class="sxs-lookup"><span data-stu-id="23147-p173">The following is an example of the `result` parameter passed to the callback function. The `value` property contains the item ID of the item.</span></span>

```
{
  "value":"AAMkADI5...AAA=",
  "status":"succeeded"
}
```

####  <a name="setselecteddataasyncdata-options-callback"></a><span data-ttu-id="23147-1115">setSelectedDataAsync(data, [options], callback)</span><span class="sxs-lookup"><span data-stu-id="23147-1115">setSelectedDataAsync(data, [options], callback)</span></span>

<span data-ttu-id="23147-1116">Асинхронно вставляет данные в текст или тему сообщения.</span><span class="sxs-lookup"><span data-stu-id="23147-1116">Asynchronously inserts data into the body or subject of a message.</span></span>

<span data-ttu-id="23147-p174">Метод `setSelectedDataAsync` вставляет указанную строку в местоположение курсора в теме или тексте элемента либо, если текст выделен в редакторе, он заменяет выделенный текст. Если курсор находится вне текста или темы элемента, возвращается ошибка. После вставки курсор помещается в конец вставленного содержимого.</span><span class="sxs-lookup"><span data-stu-id="23147-p174">The `setSelectedDataAsync` method inserts the specified string at the cursor location in the subject or body of the item, or, if text is selected in the editor, it replaces the selected text. If the cursor is not in the body or subject field, an error is returned. After insertion, the cursor is placed at the end of the inserted content.</span></span>

##### <a name="parameters"></a><span data-ttu-id="23147-1120">Параметры</span><span class="sxs-lookup"><span data-stu-id="23147-1120">Parameters:</span></span>

|<span data-ttu-id="23147-1121">Имя</span><span class="sxs-lookup"><span data-stu-id="23147-1121">Name</span></span>| <span data-ttu-id="23147-1122">Тип</span><span class="sxs-lookup"><span data-stu-id="23147-1122">Type</span></span>| <span data-ttu-id="23147-1123">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="23147-1123">Attributes</span></span>| <span data-ttu-id="23147-1124">Описание</span><span class="sxs-lookup"><span data-stu-id="23147-1124">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="23147-1125">String</span><span class="sxs-lookup"><span data-stu-id="23147-1125">String</span></span>||<span data-ttu-id="23147-p175">Вставляемые данные. Объем данных не должен превышать 1 000 000 символов. Если передано больше 1 000 000 символов, возвращается исключение `ArgumentOutOfRange`.</span><span class="sxs-lookup"><span data-stu-id="23147-p175">The data to be inserted. Data is not to exceed 1,000,000 characters. If more than 1,000,000 characters are passed in, an `ArgumentOutOfRange` exception is thrown.</span></span>|
|`options`| <span data-ttu-id="23147-1129">Object</span><span class="sxs-lookup"><span data-stu-id="23147-1129">Object</span></span>| <span data-ttu-id="23147-1130">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1130">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1131">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="23147-1131">An object literal that contains one or more of the following properties.</span></span>|
|`options.asyncContext`| <span data-ttu-id="23147-1132">Object</span><span class="sxs-lookup"><span data-stu-id="23147-1132">Object</span></span>| <span data-ttu-id="23147-1133">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1133">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-1134">В методе обратного вызова разработчики могут указать любой объект, к которому необходимо получить доступ.</span><span class="sxs-lookup"><span data-stu-id="23147-1134">Developers can provide any object they wish to access in the callback method.</span></span>|
|`options.coercionType`| [<span data-ttu-id="23147-1135">Office.CoercionType</span><span class="sxs-lookup"><span data-stu-id="23147-1135">Office.CoercionType</span></span>](office.md#coerciontype-string)| <span data-ttu-id="23147-1136">&lt;необязательный&gt;</span><span class="sxs-lookup"><span data-stu-id="23147-1136">&lt;optional&gt;</span></span>|<span data-ttu-id="23147-p176">Если задано значение `text`, текущий стиль применяется в Outlook Web App и Outlook. Если поле представляет собой редактор HTML, вставляются только текстовые данные, даже если они имеют формат HTML.</span><span class="sxs-lookup"><span data-stu-id="23147-p176">If `text`, the current style is applied in Outlook Web App and Outlook. If the field is an HTML editor, only the text data is inserted, even if the data is HTML.</span></span><br/><br/><span data-ttu-id="23147-p177">Если задано значение `html` и поле (не тема) поддерживает HTML, в Outlook Web App применяется текущий стиль, а в Outlook — стиль по умолчанию. Если поле является текстовым, возвращается ошибка `InvalidDataFormat`.</span><span class="sxs-lookup"><span data-stu-id="23147-p177">If `html` and the field supports HTML (the subject doesn't), the current style is applied in Outlook Web App and the default style is applied in Outlook. If the field is a text field, an `InvalidDataFormat` error is returned.</span></span><br/><br/><span data-ttu-id="23147-1141">Если свойство `coercionType` не задано, результат зависит от поля: если поле имеет формат HTML, используется текст в формате HTML, а если поле текстовое, применяется обычный текст.</span><span class="sxs-lookup"><span data-stu-id="23147-1141">If `coercionType` is not set, the result depends on the field: if the field is HTML then HTML is used; if the field is text, then plain text is used.</span></span>|
|`callback`| <span data-ttu-id="23147-1142">функция</span><span class="sxs-lookup"><span data-stu-id="23147-1142">function</span></span>||<span data-ttu-id="23147-1143">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="23147-1143">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="23147-1144">Требования</span><span class="sxs-lookup"><span data-stu-id="23147-1144">Requirements</span></span>

|<span data-ttu-id="23147-1145">Requirement</span><span class="sxs-lookup"><span data-stu-id="23147-1145">Requirement</span></span>| <span data-ttu-id="23147-1146">Значение</span><span class="sxs-lookup"><span data-stu-id="23147-1146">Value</span></span>|
|---|---|
|[<span data-ttu-id="23147-1147">Минимальная версия набора обязательных элементов для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="23147-1147">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="23147-1148">1.2</span><span class="sxs-lookup"><span data-stu-id="23147-1148">1.2</span></span>|
|[<span data-ttu-id="23147-1149">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="23147-1149">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="23147-1150">ReadWriteItem</span><span class="sxs-lookup"><span data-stu-id="23147-1150">ReadWriteItem</span></span>|
|[<span data-ttu-id="23147-1151">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="23147-1151">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="23147-1152">Создание</span><span class="sxs-lookup"><span data-stu-id="23147-1152">Compose</span></span>|

##### <a name="example"></a><span data-ttu-id="23147-1153">Пример</span><span class="sxs-lookup"><span data-stu-id="23147-1153">Example</span></span>

```
Office.context.mailbox.item.setSelectedDataAsync("Hello World!");
Office.context.mailbox.item.setSelectedDataAsync("<b>Hello World!</b>", { coercionType : "html" });
```