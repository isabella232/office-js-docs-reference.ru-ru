
# <a name="mailbox"></a><span data-ttu-id="132d5-101">mailbox</span><span class="sxs-lookup"><span data-stu-id="132d5-101">mailbox</span></span>

### <span data-ttu-id="132d5-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span><span class="sxs-lookup"><span data-stu-id="132d5-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span></span>

<span data-ttu-id="132d5-104">Предоставляет доступ для добавления в объектной модели Outlook для Microsoft Outlook и Microsoft Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="132d5-104">Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

##### <a name="requirements"></a><span data-ttu-id="132d5-105">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-105">Requirements</span></span>

|<span data-ttu-id="132d5-106">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-106">Requirement</span></span>| <span data-ttu-id="132d5-107">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-108">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-109">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-109">1.0</span></span>|
|[<span data-ttu-id="132d5-110">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-111">Restricted</span><span class="sxs-lookup"><span data-stu-id="132d5-111">Restricted</span></span>|
|[<span data-ttu-id="132d5-112">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-113">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-113">Compose or read</span></span>|

### <a name="namespaces"></a><span data-ttu-id="132d5-114">Пространства имен</span><span class="sxs-lookup"><span data-stu-id="132d5-114">Namespaces</span></span>

<span data-ttu-id="132d5-115">[diagnostics](Office.context.mailbox.diagnostics.md). Предоставляет надстройке Outlook диагностические сведения.</span><span class="sxs-lookup"><span data-stu-id="132d5-115">[diagnostics](Office.context.mailbox.diagnostics.md): Provides diagnostic information to an Outlook add-in.</span></span>

<span data-ttu-id="132d5-116">[item](Office.context.mailbox.item.md). Предоставляет методы и свойства для доступа к сообщению или встрече в надстройке Outlook.</span><span class="sxs-lookup"><span data-stu-id="132d5-116">[item](Office.context.mailbox.item.md): Provides methods and properties for accessing a message or appointment in an Outlook add-in.</span></span>

<span data-ttu-id="132d5-117">[userProfile](Office.context.mailbox.userProfile.md). Предоставляет сведения о пользователе в надстройке Outlook.</span><span class="sxs-lookup"><span data-stu-id="132d5-117">[userProfile](Office.context.mailbox.userProfile.md): Provides information about the user in an Outlook add-in.</span></span>

### <a name="members"></a><span data-ttu-id="132d5-118">Элементы</span><span class="sxs-lookup"><span data-stu-id="132d5-118">Members</span></span>

#### <a name="ewsurl-string"></a><span data-ttu-id="132d5-119">ewsUrl :String</span><span class="sxs-lookup"><span data-stu-id="132d5-119">ewsUrl :String</span></span>

<span data-ttu-id="132d5-p102">Получает URL-адрес конечной точки веб-служб Exchange (EWS) для этой учетной записи электронной почты. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="132d5-p102">Gets the URL of the Exchange Web Services (EWS) endpoint for this email account. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-122">Этот член не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-122">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-p103">Удаленная служба может использовать значение `ewsUrl`, чтобы выполнять вызовы EWS для почтового ящика пользователя. Например, вы можете создать удаленную службу, чтобы [получить вложения из выбранного элемента](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="132d5-p103">The `ewsUrl` value can be used by a remote service to make EWS calls to the user's mailbox. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="132d5-125">Чтобы вызвать элемент `ewsUrl` в режиме чтения, в манифесте приложения должно быть указано разрешение **ReadItem**.</span><span class="sxs-lookup"><span data-stu-id="132d5-125">Your app must have the **ReadItem** permission specified in its manifest to call the `ewsUrl` member in read mode.</span></span>

<span data-ttu-id="132d5-p104">Перед использованием элемента `ewsUrl` в режиме создания необходимо вызвать метод [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback). Для вызова метода `saveAsync` приложение должно иметь разрешения **ReadWriteItem**.</span><span class="sxs-lookup"><span data-stu-id="132d5-p104">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `ewsUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="132d5-128">Тип:</span><span class="sxs-lookup"><span data-stu-id="132d5-128">Type:</span></span>

*   <span data-ttu-id="132d5-129">String</span><span class="sxs-lookup"><span data-stu-id="132d5-129">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="132d5-130">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-130">Requirements</span></span>

|<span data-ttu-id="132d5-131">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-131">Requirement</span></span>| <span data-ttu-id="132d5-132">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-132">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-133">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-133">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-134">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-134">1.0</span></span>|
|[<span data-ttu-id="132d5-135">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-135">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-136">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-136">ReadItem</span></span>|
|[<span data-ttu-id="132d5-137">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-137">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-138">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-138">Compose or read</span></span>|

### <a name="methods"></a><span data-ttu-id="132d5-139">Методы</span><span class="sxs-lookup"><span data-stu-id="132d5-139">Methods</span></span>

####  <a name="converttoewsiditemid-restversion--string"></a><span data-ttu-id="132d5-140">convertToEwsId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="132d5-140">convertToEwsId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="132d5-141">Преобразовывает идентификатор элемента из формата REST в формат EWS.</span><span class="sxs-lookup"><span data-stu-id="132d5-141">Converts an item ID formatted for REST into EWS format.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-142">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-142">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-p105">Формат идентификаторов, извлекаемых через API REST (например, [API Почты Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) или [Microsoft Graph](http://graph.microsoft.io/)), отличается от формата веб-служб Exchange (EWS). Метод `convertToEwsId` преобразовывает идентификатор в формате REST в формат EWS.</span><span class="sxs-lookup"><span data-stu-id="132d5-p105">Item IDs retrieved via a REST API (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)) use a different format than the format used by Exchange Web Services (EWS). The `convertToEwsId` method converts a REST-formatted ID into the proper format for EWS.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-145">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-145">Parameters:</span></span>

|<span data-ttu-id="132d5-146">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-146">Name</span></span>| <span data-ttu-id="132d5-147">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-147">Type</span></span>| <span data-ttu-id="132d5-148">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-148">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="132d5-149">String</span><span class="sxs-lookup"><span data-stu-id="132d5-149">String</span></span>|<span data-ttu-id="132d5-150">Идентификатор элемента в формате REST API для Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-150">An item ID formatted for the Outlook REST APIs</span></span>|
|`restVersion`| [<span data-ttu-id="132d5-151">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="132d5-151">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook_1_3/office.mailboxenums.restversion)|<span data-ttu-id="132d5-152">Значение, определяющее версию REST API для Outlook, которая используется для извлечения идентификатора элемента.</span><span class="sxs-lookup"><span data-stu-id="132d5-152">A value indicating the version of the Outlook REST API used to retrieve the item ID.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-153">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-153">Requirements</span></span>

|<span data-ttu-id="132d5-154">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-154">Requirement</span></span>| <span data-ttu-id="132d5-155">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-155">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-156">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-156">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-157">1.3</span><span class="sxs-lookup"><span data-stu-id="132d5-157">1.3</span></span>|
|[<span data-ttu-id="132d5-158">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-158">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-159">Restricted</span><span class="sxs-lookup"><span data-stu-id="132d5-159">Restricted</span></span>|
|[<span data-ttu-id="132d5-160">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-160">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-161">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-161">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="132d5-162">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="132d5-162">Returns:</span></span>

<span data-ttu-id="132d5-163">Тип: String</span><span class="sxs-lookup"><span data-stu-id="132d5-163">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="132d5-164">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-164">Example</span></span>

```
// Get an item's ID from a REST API
var restId = 'AAMkAGVlOTZjNTM3LW...';

// Treat restId as coming from the v2.0 version of the
// Outlook Mail API
var ewsId = Office.context.mailbox.convertToEwsId(restId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttolocalclienttimetimevalue--localclienttimejavascriptapioutlook13officelocalclienttime"></a><span data-ttu-id="132d5-165">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook_1_3/office.LocalClientTime)}</span><span class="sxs-lookup"><span data-stu-id="132d5-165">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook_1_3/office.LocalClientTime)}</span></span>

<span data-ttu-id="132d5-166">Получает словарь, содержащий сведения о локальном времени клиента.</span><span class="sxs-lookup"><span data-stu-id="132d5-166">Gets a dictionary containing time information in local client time.</span></span>

<span data-ttu-id="132d5-p106">В случае дат и времени в почтовом приложении для Outlook или Outlook Web App могут использоваться разные часовые пояса. Outlook использует часовой пояс клиентского компьютера. Outlook Web App использует часовой пояс, заданный в Центре администрирования Exchange (EAC). Значения даты и времени должны обрабатываться так, чтобы значения в пользовательском интерфейсе всегда согласовывались с часовым поясом, ожидаемым пользователем.</span><span class="sxs-lookup"><span data-stu-id="132d5-p106">The dates and times used by a mail app for Outlook or Outlook Web App can use different time zones. Outlook uses the client computer time zone; Outlook Web App uses the time zone set on the Exchange Admin Center (EAC). You should handle date and time values so that the values you display on the user interface are always consistent with the time zone that the user expects.</span></span>

<span data-ttu-id="132d5-p107">Если почтовое приложение работает в Outlook, метод `convertToLocalClientTime` вернет объект словаря со значениями часового пояса клиентского компьютера. Если почтовое приложение работает в Outlook Web App, метод `convertToLocalClientTime` вернет объект словаря со значениями часового пояса, заданного в Центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="132d5-p107">If the mail app is running in Outlook, the `convertToLocalClientTime` method will return a dictionary object with the values set to the client computer time zone. If the mail app is running in Outlook Web App, the `convertToLocalClientTime` method will return a dictionary object with the values set to the time zone specified in the EAC.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-172">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-172">Parameters:</span></span>

|<span data-ttu-id="132d5-173">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-173">Name</span></span>| <span data-ttu-id="132d5-174">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-174">Type</span></span>| <span data-ttu-id="132d5-175">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-175">Description</span></span>|
|---|---|---|
|`timeValue`| <span data-ttu-id="132d5-176">Date</span><span class="sxs-lookup"><span data-stu-id="132d5-176">Date</span></span>|<span data-ttu-id="132d5-177">Объект Date</span><span class="sxs-lookup"><span data-stu-id="132d5-177">A Date object</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-178">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-178">Requirements</span></span>

|<span data-ttu-id="132d5-179">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-179">Requirement</span></span>| <span data-ttu-id="132d5-180">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-180">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-181">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-181">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-182">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-182">1.0</span></span>|
|[<span data-ttu-id="132d5-183">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-183">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-184">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-184">ReadItem</span></span>|
|[<span data-ttu-id="132d5-185">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-185">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-186">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-186">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="132d5-187">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="132d5-187">Returns:</span></span>

<span data-ttu-id="132d5-188">Тип: [LocalClientTime](/javascript/api/outlook_1_3/office.LocalClientTime)</span><span class="sxs-lookup"><span data-stu-id="132d5-188">Type: [LocalClientTime](/javascript/api/outlook_1_3/office.LocalClientTime)</span></span>

####  <a name="converttorestiditemid-restversion--string"></a><span data-ttu-id="132d5-189">convertToRestId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="132d5-189">convertToRestId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="132d5-190">Преобразовывает идентификатор элемента в формате EWS в формат REST.</span><span class="sxs-lookup"><span data-stu-id="132d5-190">Converts an item ID formatted for EWS into REST format.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-191">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-191">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-p108">Формат идентификаторов, извлекаемых через EWS или свойство `itemId`, отличается от формата API REST (таких как [API Почты Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) или [Microsoft Graph](http://graph.microsoft.io/)). Метод `convertToRestId` преобразовывает идентификатор в формате EWS в формат REST.</span><span class="sxs-lookup"><span data-stu-id="132d5-p108">Item IDs retrieved via EWS or via the `itemId` property use a different format than the format used by REST APIs (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)). The `convertToRestId` method converts an EWS-formatted ID into the proper format for REST.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-194">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-194">Parameters:</span></span>

|<span data-ttu-id="132d5-195">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-195">Name</span></span>| <span data-ttu-id="132d5-196">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-196">Type</span></span>| <span data-ttu-id="132d5-197">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-197">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="132d5-198">String</span><span class="sxs-lookup"><span data-stu-id="132d5-198">String</span></span>|<span data-ttu-id="132d5-199">Идентификатор элемента в формате EWS</span><span class="sxs-lookup"><span data-stu-id="132d5-199">An item ID formatted for Exchange Web Services (EWS)</span></span>|
|`restVersion`| [<span data-ttu-id="132d5-200">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="132d5-200">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook_1_3/office.mailboxenums.restversion)|<span data-ttu-id="132d5-201">Значение, определяющее версию REST API для Outlook, с которой будет использоваться преобразованный идентификатор.</span><span class="sxs-lookup"><span data-stu-id="132d5-201">A value indicating the version of the Outlook REST API that the converted ID will be used with.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-202">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-202">Requirements</span></span>

|<span data-ttu-id="132d5-203">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-203">Requirement</span></span>| <span data-ttu-id="132d5-204">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-204">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-205">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-205">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-206">1.3</span><span class="sxs-lookup"><span data-stu-id="132d5-206">1.3</span></span>|
|[<span data-ttu-id="132d5-207">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-207">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-208">Restricted</span><span class="sxs-lookup"><span data-stu-id="132d5-208">Restricted</span></span>|
|[<span data-ttu-id="132d5-209">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-209">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-210">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-210">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="132d5-211">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="132d5-211">Returns:</span></span>

<span data-ttu-id="132d5-212">Тип: String</span><span class="sxs-lookup"><span data-stu-id="132d5-212">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="132d5-213">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-213">Example</span></span>

```
// Get the currently selected item's ID
var ewsId = Office.context.mailbox.item.itemId;

// Convert to a REST ID for the v2.0 version of the
// Outlook Mail API
var restId = Office.context.mailbox.convertToRestId(ewsId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttoutcclienttimeinput--date"></a><span data-ttu-id="132d5-214">convertToUtcClientTime(input) → {Date}</span><span class="sxs-lookup"><span data-stu-id="132d5-214">convertToUtcClientTime(input) → {Date}</span></span>

<span data-ttu-id="132d5-215">Получает объект Date из словаря, содержащего сведения о времени.</span><span class="sxs-lookup"><span data-stu-id="132d5-215">Gets a Date object from a dictionary containing time information.</span></span>

<span data-ttu-id="132d5-216">Метод `convertToUtcClientTime` преобразует словарь, содержащий локальную дату и время, в объект Date с правильными значениями локальной даты и времени.</span><span class="sxs-lookup"><span data-stu-id="132d5-216">The `convertToUtcClientTime` method converts a dictionary containing a local date and time to a Date object with the correct values for the local date and time.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-217">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-217">Parameters:</span></span>

|<span data-ttu-id="132d5-218">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-218">Name</span></span>| <span data-ttu-id="132d5-219">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-219">Type</span></span>| <span data-ttu-id="132d5-220">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-220">Description</span></span>|
|---|---|---|
|`input`| [<span data-ttu-id="132d5-221">LocalClientTime</span><span class="sxs-lookup"><span data-stu-id="132d5-221">LocalClientTime</span></span>](/javascript/api/outlook_1_3/office.LocalClientTime)|<span data-ttu-id="132d5-222">Значение локального времени для преобразования.</span><span class="sxs-lookup"><span data-stu-id="132d5-222">The local time value to convert.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-223">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-223">Requirements</span></span>

|<span data-ttu-id="132d5-224">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-224">Requirement</span></span>| <span data-ttu-id="132d5-225">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-225">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-226">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-226">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-227">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-227">1.0</span></span>|
|[<span data-ttu-id="132d5-228">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-228">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-229">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-229">ReadItem</span></span>|
|[<span data-ttu-id="132d5-230">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-230">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-231">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-231">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="132d5-232">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="132d5-232">Returns:</span></span>

<span data-ttu-id="132d5-233">Объект Date со временем в формате UTC.</span><span class="sxs-lookup"><span data-stu-id="132d5-233">A Date object with the time expressed in UTC.</span></span>

<dl class="param-type"><span data-ttu-id="132d5-234">

<dt>Тип</dt>

</span><span class="sxs-lookup"><span data-stu-id="132d5-234">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="132d5-235">Date</span><span class="sxs-lookup"><span data-stu-id="132d5-235">Date</span></span></dd>

</dl>

####  <a name="displayappointmentformitemid"></a><span data-ttu-id="132d5-236">displayAppointmentForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="132d5-236">displayAppointmentForm(itemId)</span></span>

<span data-ttu-id="132d5-237">Отображает имеющуюся встречу из календаря.</span><span class="sxs-lookup"><span data-stu-id="132d5-237">Displays an existing calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-238">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-238">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-239">Метод `displayAppointmentForm` открывает новое окно на компьютере или диалоговое окно на мобильном устройстве, содержащее сведения календаря о существующей встрече.</span><span class="sxs-lookup"><span data-stu-id="132d5-239">The `displayAppointmentForm` method opens an existing calendar appointment in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="132d5-p109">В Outlook для Mac с помощью этого метода можно отобразить одну встречу, которая не является частью повторяющегося ряда, или основную встречу такого ряда, но не экземпляр из него, так как в Outlook для Mac невозможно получить доступ к свойствам экземпляра повторяющегося ряда (в том числе к идентификатору элемента).</span><span class="sxs-lookup"><span data-stu-id="132d5-p109">In Outlook for Mac, you can use this method to display a single appointment that is not part of a recurring series, or the master appointment of a recurring series, but you cannot display an instance of the series. This is because in Outlook for Mac, you cannot access the properties (including the item ID) of instances of a recurring series.</span></span>

<span data-ttu-id="132d5-242">В Outlook Web App этот метод открывает указанную форму, только если текст формы содержит символы размером не более 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="132d5-242">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32KB number of characters.</span></span>

<span data-ttu-id="132d5-243">Если указанный идентификатор элемента не определяет существующую встречу, на клиентском компьютере или устройстве открывается пустая страница, и сообщение об ошибке не возвращается.</span><span class="sxs-lookup"><span data-stu-id="132d5-243">If the specified item identifier does not identify an existing appointment, a blank pane opens on the client computer or device, and no error message will be returned.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-244">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-244">Parameters:</span></span>

|<span data-ttu-id="132d5-245">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-245">Name</span></span>| <span data-ttu-id="132d5-246">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-246">Type</span></span>| <span data-ttu-id="132d5-247">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-247">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="132d5-248">String</span><span class="sxs-lookup"><span data-stu-id="132d5-248">String</span></span>|<span data-ttu-id="132d5-249">Идентификатор веб-служб Exchange для существующей встречи в календаре.</span><span class="sxs-lookup"><span data-stu-id="132d5-249">The Exchange Web Services (EWS) identifier for an existing calendar appointment.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-250">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-250">Requirements</span></span>

|<span data-ttu-id="132d5-251">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-251">Requirement</span></span>| <span data-ttu-id="132d5-252">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-252">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-253">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-253">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-254">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-254">1.0</span></span>|
|[<span data-ttu-id="132d5-255">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-255">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-256">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-256">ReadItem</span></span>|
|[<span data-ttu-id="132d5-257">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-257">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-258">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-258">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-259">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-259">Example</span></span>

```
Office.context.mailbox.displayAppointmentForm(appointmentId);
```

####  <a name="displaymessageformitemid"></a><span data-ttu-id="132d5-260">displayMessageForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="132d5-260">displayMessageForm(itemId)</span></span>

<span data-ttu-id="132d5-261">Отображает имеющееся сообщение.</span><span class="sxs-lookup"><span data-stu-id="132d5-261">Displays an existing message.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-262">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-262">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-263">Метод `displayMessageForm` открывает новое окно на компьютере или диалоговое окно на мобильном устройстве, содержащее существующее сообщение.</span><span class="sxs-lookup"><span data-stu-id="132d5-263">The `displayMessageForm` method opens an existing message in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="132d5-264">В Outlook Web App этот метод открывает указанную форму, только если текст формы содержит символы размером не более 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="132d5-264">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32 KB number of characters.</span></span>

<span data-ttu-id="132d5-265">Если указанный идентификатор элемента не определяет существующее сообщение, окно на клиентском компьютере не открывается и сообщение об ошибке не возвращается.</span><span class="sxs-lookup"><span data-stu-id="132d5-265">If the specified item identifier does not identify an existing message, no message will be displayed on the client computer, and no error message will be returned.</span></span>

<span data-ttu-id="132d5-p110">Не используйте `displayMessageForm` с параметром `itemId`, который представляет собой встречу. Используйте метод `displayAppointmentForm`, чтобы отобразить сведения о существующей встрече, а метод `displayNewAppointmentForm` — для отображения формы создания встречи.</span><span class="sxs-lookup"><span data-stu-id="132d5-p110">Do not use the `displayMessageForm` with an `itemId` that represents an appointment. Use the `displayAppointmentForm` method to display an existing appointment, and `displayNewAppointmentForm` to display a form to create a new appointment.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-268">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-268">Parameters:</span></span>

|<span data-ttu-id="132d5-269">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-269">Name</span></span>| <span data-ttu-id="132d5-270">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-270">Type</span></span>| <span data-ttu-id="132d5-271">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-271">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="132d5-272">String</span><span class="sxs-lookup"><span data-stu-id="132d5-272">String</span></span>|<span data-ttu-id="132d5-273">Идентификатор веб-служб Exchange для существующего сообщения.</span><span class="sxs-lookup"><span data-stu-id="132d5-273">The Exchange Web Services (EWS) identifier for an existing message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-274">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-274">Requirements</span></span>

|<span data-ttu-id="132d5-275">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-275">Requirement</span></span>| <span data-ttu-id="132d5-276">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-276">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-277">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-277">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-278">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-278">1.0</span></span>|
|[<span data-ttu-id="132d5-279">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-279">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-280">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-280">ReadItem</span></span>|
|[<span data-ttu-id="132d5-281">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-281">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-282">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-282">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-283">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-283">Example</span></span>

```
Office.context.mailbox.displayMessageForm(messageId);
```

#### <a name="displaynewappointmentformparameters"></a><span data-ttu-id="132d5-284">displayNewAppointmentForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="132d5-284">displayNewAppointmentForm(parameters)</span></span>

<span data-ttu-id="132d5-285">Отображает форму для создания новой встречи в календаре.</span><span class="sxs-lookup"><span data-stu-id="132d5-285">Displays a form for creating a new calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-286">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="132d5-286">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="132d5-p111">Метод `displayNewAppointmentForm` открывает форму, в которой пользователь может создать встречу или собрание. Если параметры заданы, поля формы встречи автоматически заполняются их содержимым.</span><span class="sxs-lookup"><span data-stu-id="132d5-p111">The `displayNewAppointmentForm` method opens a form that enables the user to create a new appointment or meeting. If parameters are specified, the appointment form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="132d5-p112">В Outlook Web App и Outlook Web App для устройств этот метод всегда отображает форму с полем участников. Если вы не укажете участников в качестве входных аргументов, метод отображает форму с кнопкой **Сохранить**. Если вы укажете участников, форма будет включать участников и кнопку **Отправить**.</span><span class="sxs-lookup"><span data-stu-id="132d5-p112">In Outlook Web App and OWA for Devices, this method always displays a form with an attendees field. If you do not specify any attendees as input arguments, the method displays a form with a **Save** button. If you have specified attendees, the form would include the attendees and a **Send** button.</span></span>

<span data-ttu-id="132d5-p113">Если вы укажете участников или ресурсы с помощью параметра `requiredAttendees`, `optionalAttendees` или `resources` в клиенте Outlook с расширенными возможностями и Outlook RT, этот метод отобразит форму собрания с кнопкой **Отправить**. Если не указать получателей, этот метод отобразит форму встречи с кнопкой **Сохранить и закрыть**.</span><span class="sxs-lookup"><span data-stu-id="132d5-p113">In the Outlook rich client and Outlook RT, if you specify any attendees or resources in the `requiredAttendees`, `optionalAttendees`, or `resources` parameter, this method displays a meeting form with a **Send** button. If you don't specify any recipients, this method displays an appointment form with a **Save & Close** button.</span></span>

<span data-ttu-id="132d5-294">Если параметры превышают указанные ограничения размера или если указано неизвестное имя параметра, вызывается исключение.</span><span class="sxs-lookup"><span data-stu-id="132d5-294">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-295">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-295">Parameters:</span></span>

|<span data-ttu-id="132d5-296">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-296">Name</span></span>| <span data-ttu-id="132d5-297">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-297">Type</span></span>| <span data-ttu-id="132d5-298">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-298">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="132d5-299">Object</span><span class="sxs-lookup"><span data-stu-id="132d5-299">Object</span></span> | <span data-ttu-id="132d5-300">Словарь параметров, описывающий новую встречу.</span><span class="sxs-lookup"><span data-stu-id="132d5-300">A dictionary of parameters describing the new appointment.</span></span> |
| `parameters.requiredAttendees` | <span data-ttu-id="132d5-301">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_3/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-301">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_3/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="132d5-p114">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из обязательных участников встречи. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="132d5-p114">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the required attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.optionalAttendees` | <span data-ttu-id="132d5-304">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_3/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-304">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook_1_3/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="132d5-p115">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из необязательных участников встречи. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="132d5-p115">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the optional attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.start` | <span data-ttu-id="132d5-307">Date</span><span class="sxs-lookup"><span data-stu-id="132d5-307">Date</span></span> | <span data-ttu-id="132d5-308">Объект `Date`, указывающий дату и время начала встречи.</span><span class="sxs-lookup"><span data-stu-id="132d5-308">A `Date` object specifying the start date and time of the appointment.</span></span> |
| `parameters.end` | <span data-ttu-id="132d5-309">Date</span><span class="sxs-lookup"><span data-stu-id="132d5-309">Date</span></span> | <span data-ttu-id="132d5-310">Объект `Date`, указывающий дату и время окончания встречи.</span><span class="sxs-lookup"><span data-stu-id="132d5-310">A `Date` object specifying the end date and time of the appointment.</span></span> |
| `parameters.location` | <span data-ttu-id="132d5-311">String</span><span class="sxs-lookup"><span data-stu-id="132d5-311">String</span></span> | <span data-ttu-id="132d5-p116">Строка со сведениями о месте встречи. Максимальное количество символов в строке — 255.</span><span class="sxs-lookup"><span data-stu-id="132d5-p116">A string containing the location of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.resources` | <span data-ttu-id="132d5-314">Array.&lt;String&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-314">Array.&lt;String&gt;</span></span> | <span data-ttu-id="132d5-p117">Массив строк, содержащий необходимые для встречи ресурсы. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="132d5-p117">An array of strings containing the resources required for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="132d5-317">String</span><span class="sxs-lookup"><span data-stu-id="132d5-317">String</span></span> | <span data-ttu-id="132d5-p118">Строка с темой встречи. Максимальное количество символов в строке — 255.</span><span class="sxs-lookup"><span data-stu-id="132d5-p118">A string containing the subject of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.body` | <span data-ttu-id="132d5-320">String</span><span class="sxs-lookup"><span data-stu-id="132d5-320">String</span></span> | <span data-ttu-id="132d5-p119">Текст сообщения о встрече. Максимальный размер содержимого сообщения — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="132d5-p119">The body of the appointment. The body content is limited to a maximum size of 32 KB.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="132d5-323">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-323">Requirements</span></span>

|<span data-ttu-id="132d5-324">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-324">Requirement</span></span>| <span data-ttu-id="132d5-325">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-325">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-326">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-326">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-327">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-327">1.0</span></span>|
|[<span data-ttu-id="132d5-328">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-328">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-329">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-329">ReadItem</span></span>|
|[<span data-ttu-id="132d5-330">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-330">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-331">Чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-331">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-332">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-332">Example</span></span>

```
var start = new Date();
var end = new Date();
end.setHours(start.getHours() + 1);

Office.context.mailbox.displayNewAppointmentForm(
  {
    requiredAttendees: ['bob@contoso.com'],
    optionalAttendees: ['sam@contoso.com'],
    start: start,
    end: end,
    location: 'Home',
    resources: ['projector@contoso.com'],
    subject: 'meeting',
    body: 'Hello World!'
  });
```

#### <a name="getcallbacktokenasynccallback-usercontext"></a><span data-ttu-id="132d5-333">getCallbackTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="132d5-333">getCallbackTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="132d5-334">Получает строку, содержащую маркер, используемый для получения вложения или элемента с Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="132d5-334">Gets a string that contains a token used to get an attachment or item from an Exchange Server.</span></span>

<span data-ttu-id="132d5-p120">Метод `getCallbackTokenAsync` совершает асинхронный вызов, чтобы получить непрозрачный токен с сервера Exchange Server, на котором размещен почтовый ящик пользователя. Время существования маркера обратного вызова составляет 5 минут.</span><span class="sxs-lookup"><span data-stu-id="132d5-p120">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

<span data-ttu-id="132d5-p121">Вы можете передать сторонней системе токен и идентификатор вложения или элемента. Сторонняя система использует этот токен как токен авторизации, чтобы вызвать операцию [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) или [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) веб-служб Exchange для возврата вложения или элемента. Например, вы можете создать удаленную службу, чтобы [получить вложения из выбранного элемента](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="132d5-p121">You can pass the token and an attachment identifier or item identifier to a third-party system. The third-party system uses the token as a bearer authorization token to call the Exchange Web Services (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) or [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) operation to return an attachment or item. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="132d5-340">Для вызова метода `getCallbackTokenAsync` в режиме чтения манифесте приложения должно быть указано разрешение **ReadItem**.</span><span class="sxs-lookup"><span data-stu-id="132d5-340">Your app must have the **ReadItem** permission specified in its manifest to call the `getCallbackTokenAsync` method in read mode.</span></span>

<span data-ttu-id="132d5-p122">Чтобы получить идентификатор элемента для передачи в метод `getCallbackTokenAsync`, в режиме создания необходимо вызвать метод [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback). Для вызова метода `saveAsync` приложение должно иметь разрешения **ReadWriteItem**.</span><span class="sxs-lookup"><span data-stu-id="132d5-p122">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method to get an item identifier to pass to the `getCallbackTokenAsync` method. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-343">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-343">Parameters:</span></span>

|<span data-ttu-id="132d5-344">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-344">Name</span></span>| <span data-ttu-id="132d5-345">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-345">Type</span></span>| <span data-ttu-id="132d5-346">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="132d5-346">Attributes</span></span>| <span data-ttu-id="132d5-347">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-347">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="132d5-348">function</span><span class="sxs-lookup"><span data-stu-id="132d5-348">function</span></span>||<span data-ttu-id="132d5-p123">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult). Токен указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="132d5-p123">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="132d5-351">Объект</span><span class="sxs-lookup"><span data-stu-id="132d5-351">Object</span></span>| <span data-ttu-id="132d5-352">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-352">&lt;optional&gt;</span></span>|<span data-ttu-id="132d5-353">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="132d5-353">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-354">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-354">Requirements</span></span>

|<span data-ttu-id="132d5-355">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-355">Requirement</span></span>| <span data-ttu-id="132d5-356">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-356">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-357">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-357">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-358">1.3</span><span class="sxs-lookup"><span data-stu-id="132d5-358">1.3</span></span>|
|[<span data-ttu-id="132d5-359">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-359">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-360">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-360">ReadItem</span></span>|
|[<span data-ttu-id="132d5-361">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-361">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-362">Создание и чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-362">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-363">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-363">Example</span></span>

```js
function getCallbackToken() {
  Office.context.mailbox.getCallbackTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="getuseridentitytokenasynccallback-usercontext"></a><span data-ttu-id="132d5-364">getUserIdentityTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="132d5-364">getUserIdentityTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="132d5-365">Получает маркер, идентифицирующий пользователя и надстройку Office.</span><span class="sxs-lookup"><span data-stu-id="132d5-365">Gets a token identifying the user and the Office Add-in.</span></span>

<span data-ttu-id="132d5-366">Метод `getUserIdentityTokenAsync` возвращает токен, который можно использовать для идентификации, а также [проверки подлинности надстройки и пользователя в сторонней системе](https://docs.microsoft.com/outlook/add-ins/authentication).</span><span class="sxs-lookup"><span data-stu-id="132d5-366">The `getUserIdentityTokenAsync` method returns a token that you can use to identify and [authenticate the add-in and user with a third-party system](https://docs.microsoft.com/outlook/add-ins/authentication).</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-367">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-367">Parameters:</span></span>

|<span data-ttu-id="132d5-368">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-368">Name</span></span>| <span data-ttu-id="132d5-369">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-369">Type</span></span>| <span data-ttu-id="132d5-370">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="132d5-370">Attributes</span></span>| <span data-ttu-id="132d5-371">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-371">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="132d5-372">function</span><span class="sxs-lookup"><span data-stu-id="132d5-372">function</span></span>||<span data-ttu-id="132d5-373">После выполнения метода функция, переданная в параметре `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="132d5-373">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="132d5-374">Токен указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="132d5-374">The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="132d5-375">Object</span><span class="sxs-lookup"><span data-stu-id="132d5-375">Object</span></span>| <span data-ttu-id="132d5-376">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-376">&lt;optional&gt;</span></span>|<span data-ttu-id="132d5-377">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="132d5-377">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-378">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-378">Requirements</span></span>

|<span data-ttu-id="132d5-379">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-379">Requirement</span></span>| <span data-ttu-id="132d5-380">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-380">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-381">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-381">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-382">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-382">1.0</span></span>|
|[<span data-ttu-id="132d5-383">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-383">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-384">ReadItem</span><span class="sxs-lookup"><span data-stu-id="132d5-384">ReadItem</span></span>|
|[<span data-ttu-id="132d5-385">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-385">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-386">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-386">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-387">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-387">Example</span></span>

```js
function getIdentityToken() {
  Office.context.mailbox.getUserIdentityTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="makeewsrequestasyncdata-callback-usercontext"></a><span data-ttu-id="132d5-388">makeEwsRequestAsync(data, callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="132d5-388">makeEwsRequestAsync(data, callback, [userContext])</span></span>

<span data-ttu-id="132d5-389">Выполняет асинхронный запрос для веб-служб Exchange (EWS) на сервере Exchange Server, на котором размещен почтовый ящик пользователя.</span><span class="sxs-lookup"><span data-stu-id="132d5-389">Makes an asynchronous request to an Exchange Web Services (EWS) service on the Exchange server that hosts the user’s mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-390">Этот метод не поддерживается в следующих случаях.</span><span class="sxs-lookup"><span data-stu-id="132d5-390">This method is not supported in the following scenarios.</span></span>
> - <span data-ttu-id="132d5-391">В Outlook для операций ввода-вывода или Outlook для Android (en)</span><span class="sxs-lookup"><span data-stu-id="132d5-391">In Outlook for iOS or Outlook for Android</span></span>
> - <span data-ttu-id="132d5-392">Когда надстройки загружается в почтовом ящике Gmail</span><span class="sxs-lookup"><span data-stu-id="132d5-392">When the add-in is loaded in a Gmail mailbox</span></span>
> 
> <span data-ttu-id="132d5-393">В таких случаях надстроек следует [использовать API -интерфейсы REST](https://docs.microsoft.com/outlook/add-ins/use-rest-api) к почтового ящика пользователя.</span><span class="sxs-lookup"><span data-stu-id="132d5-393">In these cases, add-ins should [use REST APIs](https://docs.microsoft.com/outlook/add-ins/use-rest-api) to access the user's mailbox instead.</span></span>

<span data-ttu-id="132d5-394">Метод `makeEwsRequestAsync` отправляет запрос EWS от имени надстройки в Exchange.</span><span class="sxs-lookup"><span data-stu-id="132d5-394">The `makeEwsRequestAsync` method sends an EWS request on behalf of the add-in to Exchange.</span></span> <span data-ttu-id="132d5-395">[Вызов веб-служб из надстройки Outlook](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) в разделе список поддерживаемые операции веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="132d5-395">See [Call web services from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) for a list of the supported EWS operations.</span></span>

<span data-ttu-id="132d5-396">С помощью метода `makeEwsRequestAsync` невозможно запрашивать элементы, связанные с папкой.</span><span class="sxs-lookup"><span data-stu-id="132d5-396">You cannot request Folder Associated Items with the `makeEwsRequestAsync` method.</span></span>

<span data-ttu-id="132d5-397">В запросе XML должна быть указана кодировка UTF-8.</span><span class="sxs-lookup"><span data-stu-id="132d5-397">The XML request must specify UTF-8 encoding.</span></span>

```
<?xml version="1.0" encoding="utf-8"?>
```

<span data-ttu-id="132d5-p125">У вашей надстройки должно быть разрешение **ReadWriteMailbox** для использования метода `makeEwsRequestAsync`. Сведения об использовании разрешения **ReadWriteMailbox** и операций EWS, которые можно вызывать с помощью метода `makeEwsRequestAsync`, см. в статье [Указание разрешений для доступа почтовой надстройки к почтовому ящику пользователя](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span><span class="sxs-lookup"><span data-stu-id="132d5-p125">Your add-in must have the **ReadWriteMailbox** permission to use the `makeEwsRequestAsync` method. For information about using the **ReadWriteMailbox** permission and the EWS operations that you can call with the `makeEwsRequestAsync` method, see [Specify permissions for mail add-in access to the user's mailbox](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span></span>

> [!NOTE]
> <span data-ttu-id="132d5-400">Администратор сервера должен установить `OAuthAuthentication` имеет значение true в каталоге Client Access Server EWS, чтобы включить `makeEwsRequestAsync` запрашивает метод веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="132d5-400">The server administrator must set `OAuthAuthentication` to true on the Client Access Server EWS directory to enable the `makeEwsRequestAsync` method to make EWS requests.</span></span>

##### <a name="version-differences"></a><span data-ttu-id="132d5-401">Различия версий</span><span class="sxs-lookup"><span data-stu-id="132d5-401">Version differences</span></span>

<span data-ttu-id="132d5-402">Если вы используете метод `makeEwsRequestAsync` в почтовых приложениях, которые выполняются в Outlook версии более ранней, чем 15.0.4535.1004, указывайте кодировку `ISO-8859-1`.</span><span class="sxs-lookup"><span data-stu-id="132d5-402">When you use the `makeEwsRequestAsync` method in mail apps running in Outlook versions earlier than version 15.0.4535.1004, you should set the encoding value to `ISO-8859-1`.</span></span>

```
<?xml version="1.0" encoding="iso-8859-1"?>
```

<span data-ttu-id="132d5-p126">Значение кодировки не нужно указывать, если почтовое приложение выполняется в Outlook в Интернете. Чтобы определить, выполняется ли приложение в Outlook или Outlook в Интернете, используйте свойство mailbox.diagnostics.hostName. Используемую версию Outlook можно определить с помощью свойства mailbox.diagnostics.hostVersion.</span><span class="sxs-lookup"><span data-stu-id="132d5-p126">You do not need to set the encoding value when your mail app is running in Outlook on the web. You can determine whether your mail app is running in Outlook or Outlook on the web by using the mailbox.diagnostics.hostName property. You can determine what version of Outlook is running by using the mailbox.diagnostics.hostVersion property.</span></span>

##### <a name="parameters"></a><span data-ttu-id="132d5-406">Параметры</span><span class="sxs-lookup"><span data-stu-id="132d5-406">Parameters:</span></span>

|<span data-ttu-id="132d5-407">Имя</span><span class="sxs-lookup"><span data-stu-id="132d5-407">Name</span></span>| <span data-ttu-id="132d5-408">Тип</span><span class="sxs-lookup"><span data-stu-id="132d5-408">Type</span></span>| <span data-ttu-id="132d5-409">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="132d5-409">Attributes</span></span>| <span data-ttu-id="132d5-410">Описание</span><span class="sxs-lookup"><span data-stu-id="132d5-410">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="132d5-411">String</span><span class="sxs-lookup"><span data-stu-id="132d5-411">String</span></span>||<span data-ttu-id="132d5-412">Запрос EWS.</span><span class="sxs-lookup"><span data-stu-id="132d5-412">The EWS request.</span></span>|
|`callback`| <span data-ttu-id="132d5-413">function</span><span class="sxs-lookup"><span data-stu-id="132d5-413">function</span></span>||<span data-ttu-id="132d5-414">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="132d5-414">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="132d5-415">Результат XML вызова EWS указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="132d5-415">The XML result of the EWS call is provided as a string in the `asyncResult.value` property.</span></span> <span data-ttu-id="132d5-416">Если результат превышает 1 МБ по размеру, возвращается сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="132d5-416">If the result exceeds 1 MB in size, an error message is returned instead.</span></span>|
|`userContext`| <span data-ttu-id="132d5-417">Объект</span><span class="sxs-lookup"><span data-stu-id="132d5-417">Object</span></span>| <span data-ttu-id="132d5-418">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="132d5-418">&lt;optional&gt;</span></span>|<span data-ttu-id="132d5-419">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="132d5-419">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="132d5-420">Требования</span><span class="sxs-lookup"><span data-stu-id="132d5-420">Requirements</span></span>

|<span data-ttu-id="132d5-421">Requirement</span><span class="sxs-lookup"><span data-stu-id="132d5-421">Requirement</span></span>| <span data-ttu-id="132d5-422">Значение</span><span class="sxs-lookup"><span data-stu-id="132d5-422">Value</span></span>|
|---|---|
|[<span data-ttu-id="132d5-423">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="132d5-423">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="132d5-424">1.0</span><span class="sxs-lookup"><span data-stu-id="132d5-424">1.0</span></span>|
|[<span data-ttu-id="132d5-425">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="132d5-425">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="132d5-426">ReadWriteMailbox</span><span class="sxs-lookup"><span data-stu-id="132d5-426">ReadWriteMailbox</span></span>|
|[<span data-ttu-id="132d5-427">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="132d5-427">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="132d5-428">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="132d5-428">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="132d5-429">Пример</span><span class="sxs-lookup"><span data-stu-id="132d5-429">Example</span></span>

<span data-ttu-id="132d5-430">В следующем примере вызывается `makeEwsRequestAsync` для получения темы элемента с помощью операции `GetItem`.</span><span class="sxs-lookup"><span data-stu-id="132d5-430">The following example calls `makeEwsRequestAsync` to use the `GetItem` operation to get the subject of an item.</span></span>

```js
function getSubjectRequest(id) {
   // Return a GetItem operation request for the subject of the specified item.
   var request =
    '<?xml version="1.0" encoding="utf-8"?>' +
    '<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"' +
    '               xmlns:xsd="http://www.w3.org/2001/XMLSchema"' +
    '               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"' +
    '               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">' +
    '  <soap:Header>' +
    '    <RequestServerVersion Version="Exchange2013" xmlns="http://schemas.microsoft.com/exchange/services/2006/types" soap:mustUnderstand="0" />' +
    '  </soap:Header>' +
    '  <soap:Body>' +
    '    <GetItem xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">' +
    '      <ItemShape>' +
    '        <t:BaseShape>IdOnly</t:BaseShape>' +
    '        <t:AdditionalProperties>' +
    '            <t:FieldURI FieldURI="item:Subject"/>' +
    '        </t:AdditionalProperties>' +
    '      </ItemShape>' +
    '      <ItemIds><t:ItemId Id="' + id + '"/></ItemIds>' +
    '    </GetItem>' +
    '  </soap:Body>' +
    '</soap:Envelope>';

   return request;
}

function sendRequest() {
   // Create a local variable that contains the mailbox.
   Office.context.mailbox.makeEwsRequestAsync(
    getSubjectRequest(mailbox.item.itemId), callback);
}

function callback(asyncResult)  {
   var result = asyncResult.value;
   var context = asyncResult.asyncContext;

   // Process the returned response here.
}
```