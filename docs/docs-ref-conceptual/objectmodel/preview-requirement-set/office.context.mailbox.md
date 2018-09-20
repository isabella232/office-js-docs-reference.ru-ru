
# <a name="mailbox"></a><span data-ttu-id="fc119-101">mailbox</span><span class="sxs-lookup"><span data-stu-id="fc119-101">mailbox</span></span>

### <span data-ttu-id="fc119-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span><span class="sxs-lookup"><span data-stu-id="fc119-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span></span>

<span data-ttu-id="fc119-104">Предоставляет доступ для добавления в объектной модели Outlook для Microsoft Outlook и Microsoft Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="fc119-104">Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

##### <a name="requirements"></a><span data-ttu-id="fc119-105">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-105">Requirements</span></span>

|<span data-ttu-id="fc119-106">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-106">Requirement</span></span>| <span data-ttu-id="fc119-107">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-108">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-109">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-109">1.0</span></span>|
|[<span data-ttu-id="fc119-110">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-111">Restricted</span><span class="sxs-lookup"><span data-stu-id="fc119-111">Restricted</span></span>|
|[<span data-ttu-id="fc119-112">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-113">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="fc119-114">Элементы и методы</span><span class="sxs-lookup"><span data-stu-id="fc119-114">Members and methods</span></span>

| <span data-ttu-id="fc119-115">Элемент</span><span class="sxs-lookup"><span data-stu-id="fc119-115">Member</span></span> | <span data-ttu-id="fc119-116">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="fc119-117">ewsUrl</span><span class="sxs-lookup"><span data-stu-id="fc119-117">ewsUrl</span></span>](#ewsurl-string) | <span data-ttu-id="fc119-118">Элемент</span><span class="sxs-lookup"><span data-stu-id="fc119-118">Member</span></span> |
| [<span data-ttu-id="fc119-119">restUrl</span><span class="sxs-lookup"><span data-stu-id="fc119-119">restUrl</span></span>](#resturl-string) | <span data-ttu-id="fc119-120">Элемент</span><span class="sxs-lookup"><span data-stu-id="fc119-120">Member</span></span> |
| [<span data-ttu-id="fc119-121">addHandlerAsync</span><span class="sxs-lookup"><span data-stu-id="fc119-121">addHandlerAsync</span></span>](#addhandlerasynceventtype-handler-options-callback) | <span data-ttu-id="fc119-122">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-122">Method</span></span> |
| [<span data-ttu-id="fc119-123">convertToEwsId</span><span class="sxs-lookup"><span data-stu-id="fc119-123">convertToEwsId</span></span>](#converttoewsiditemid-restversion--string) | <span data-ttu-id="fc119-124">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-124">Method</span></span> |
| [<span data-ttu-id="fc119-125">convertToLocalClientTime</span><span class="sxs-lookup"><span data-stu-id="fc119-125">convertToLocalClientTime</span></span>](#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime) | <span data-ttu-id="fc119-126">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-126">Method</span></span> |
| [<span data-ttu-id="fc119-127">convertToRestId</span><span class="sxs-lookup"><span data-stu-id="fc119-127">convertToRestId</span></span>](#converttorestiditemid-restversion--string) | <span data-ttu-id="fc119-128">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-128">Method</span></span> |
| [<span data-ttu-id="fc119-129">convertToUtcClientTime</span><span class="sxs-lookup"><span data-stu-id="fc119-129">convertToUtcClientTime</span></span>](#converttoutcclienttimeinput--date) | <span data-ttu-id="fc119-130">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-130">Method</span></span> |
| [<span data-ttu-id="fc119-131">displayAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="fc119-131">displayAppointmentForm</span></span>](#displayappointmentformitemid) | <span data-ttu-id="fc119-132">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-132">Method</span></span> |
| [<span data-ttu-id="fc119-133">displayMessageForm</span><span class="sxs-lookup"><span data-stu-id="fc119-133">displayMessageForm</span></span>](#displaymessageformitemid) | <span data-ttu-id="fc119-134">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-134">Method</span></span> |
| [<span data-ttu-id="fc119-135">displayNewAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="fc119-135">displayNewAppointmentForm</span></span>](#displaynewappointmentformparameters) | <span data-ttu-id="fc119-136">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-136">Method</span></span> |
| [<span data-ttu-id="fc119-137">displayNewMessageForm</span><span class="sxs-lookup"><span data-stu-id="fc119-137">displayNewMessageForm</span></span>](#displaynewmessageformparameters) | <span data-ttu-id="fc119-138">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-138">Method</span></span> |
| [<span data-ttu-id="fc119-139">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="fc119-139">getCallbackTokenAsync</span></span>](#getcallbacktokenasyncoptions-callback) | <span data-ttu-id="fc119-140">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-140">Method</span></span> |
| [<span data-ttu-id="fc119-141">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="fc119-141">getCallbackTokenAsync</span></span>](#getcallbacktokenasynccallback-usercontext) | <span data-ttu-id="fc119-142">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-142">Method</span></span> |
| [<span data-ttu-id="fc119-143">getUserIdentityTokenAsync</span><span class="sxs-lookup"><span data-stu-id="fc119-143">getUserIdentityTokenAsync</span></span>](#getuseridentitytokenasynccallback-usercontext) | <span data-ttu-id="fc119-144">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-144">Method</span></span> |
| [<span data-ttu-id="fc119-145">makeEwsRequestAsync</span><span class="sxs-lookup"><span data-stu-id="fc119-145">makeEwsRequestAsync</span></span>](#makeewsrequestasyncdata-callback-usercontext) | <span data-ttu-id="fc119-146">Метод</span><span class="sxs-lookup"><span data-stu-id="fc119-146">Method</span></span> |

### <a name="namespaces"></a><span data-ttu-id="fc119-147">Пространства имен</span><span class="sxs-lookup"><span data-stu-id="fc119-147">Namespaces</span></span>

<span data-ttu-id="fc119-148">[diagnostics](Office.context.mailbox.diagnostics.md). Предоставляет надстройке Outlook диагностические сведения.</span><span class="sxs-lookup"><span data-stu-id="fc119-148">[diagnostics](Office.context.mailbox.diagnostics.md): Provides diagnostic information to an Outlook add-in.</span></span>

<span data-ttu-id="fc119-149">[item](Office.context.mailbox.item.md). Предоставляет методы и свойства для доступа к сообщению или встрече в надстройке Outlook.</span><span class="sxs-lookup"><span data-stu-id="fc119-149">[item](Office.context.mailbox.item.md): Provides methods and properties for accessing a message or appointment in an Outlook add-in.</span></span>

<span data-ttu-id="fc119-150">[userProfile](Office.context.mailbox.userProfile.md). Предоставляет сведения о пользователе в надстройке Outlook.</span><span class="sxs-lookup"><span data-stu-id="fc119-150">[userProfile](Office.context.mailbox.userProfile.md): Provides information about the user in an Outlook add-in.</span></span>

### <a name="members"></a><span data-ttu-id="fc119-151">Элементы</span><span class="sxs-lookup"><span data-stu-id="fc119-151">Members</span></span>

#### <a name="ewsurl-string"></a><span data-ttu-id="fc119-152">ewsUrl :String</span><span class="sxs-lookup"><span data-stu-id="fc119-152">ewsUrl :String</span></span>

<span data-ttu-id="fc119-p102">Получает URL-адрес конечной точки веб-служб Exchange (EWS) для этой учетной записи электронной почты. Только в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="fc119-p102">Gets the URL of the Exchange Web Services (EWS) endpoint for this email account. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-155">Этот член не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-155">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-p103">Удаленная служба может использовать значение `ewsUrl`, чтобы выполнять вызовы EWS для почтового ящика пользователя. Например, вы можете создать удаленную службу, чтобы [получить вложения из выбранного элемента](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="fc119-p103">The `ewsUrl` value can be used by a remote service to make EWS calls to the user's mailbox. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="fc119-158">Чтобы вызвать элемент `ewsUrl` в режиме чтения, в манифесте приложения должно быть указано разрешение **ReadItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-158">Your app must have the **ReadItem** permission specified in its manifest to call the `ewsUrl` member in read mode.</span></span>

<span data-ttu-id="fc119-p104">Перед использованием элемента `ewsUrl` в режиме создания необходимо вызвать метод [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback). Для вызова метода `saveAsync` приложение должно иметь разрешения **ReadWriteItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-p104">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `ewsUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="fc119-161">Тип:</span><span class="sxs-lookup"><span data-stu-id="fc119-161">Type:</span></span>

*   <span data-ttu-id="fc119-162">String</span><span class="sxs-lookup"><span data-stu-id="fc119-162">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="fc119-163">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-163">Requirements</span></span>

|<span data-ttu-id="fc119-164">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-164">Requirement</span></span>| <span data-ttu-id="fc119-165">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-165">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-166">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-166">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-167">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-167">1.0</span></span>|
|[<span data-ttu-id="fc119-168">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-168">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-169">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-169">ReadItem</span></span>|
|[<span data-ttu-id="fc119-170">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-170">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-171">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-171">Compose or read</span></span>|

#### <a name="resturl-string"></a><span data-ttu-id="fc119-172">restUrl :String</span><span class="sxs-lookup"><span data-stu-id="fc119-172">restUrl :String</span></span>

<span data-ttu-id="fc119-173">Возвращает URL-адрес конечной точки REST для этой учетной записи электронной почты.</span><span class="sxs-lookup"><span data-stu-id="fc119-173">Gets the URL of the REST endpoint for this email account.</span></span>

<span data-ttu-id="fc119-174">С помощью значения `restUrl` можно выполнять вызовы [REST API](https://docs.microsoft.com/outlook/rest/) для почтового ящика пользователя.</span><span class="sxs-lookup"><span data-stu-id="fc119-174">The `restUrl` value can be used to make [REST API](https://docs.microsoft.com/outlook/rest/) calls to the user's mailbox.</span></span>

<span data-ttu-id="fc119-175">Чтобы вызвать элемент `restUrl` в режиме чтения, в манифесте приложения необходимо указать разрешение **ReadItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-175">Your app must have the **ReadItem** permission specified in its manifest to call the `restUrl` member in read mode.</span></span>

<span data-ttu-id="fc119-p105">Перед использованием элемента `restUrl` в режиме создания необходимо вызвать метод [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback). Для вызова метода `saveAsync` приложение должно иметь разрешения **ReadWriteItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-p105">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `restUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="fc119-178">Тип:</span><span class="sxs-lookup"><span data-stu-id="fc119-178">Type:</span></span>

*   <span data-ttu-id="fc119-179">String</span><span class="sxs-lookup"><span data-stu-id="fc119-179">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="fc119-180">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-180">Requirements</span></span>

|<span data-ttu-id="fc119-181">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-181">Requirement</span></span>| <span data-ttu-id="fc119-182">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-182">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-183">Минимальная версия набора обязательных элементов для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="fc119-183">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-184">1.5</span><span class="sxs-lookup"><span data-stu-id="fc119-184">1.5</span></span> |
|[<span data-ttu-id="fc119-185">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-185">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-186">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-186">ReadItem</span></span>|
|[<span data-ttu-id="fc119-187">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-187">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-188">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-188">Compose or read</span></span>|

### <a name="methods"></a><span data-ttu-id="fc119-189">Методы</span><span class="sxs-lookup"><span data-stu-id="fc119-189">Methods</span></span>

####  <a name="addhandlerasynceventtype-handler-options-callback"></a><span data-ttu-id="fc119-190">addHandlerAsync(eventType, handler, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="fc119-190">addHandlerAsync(eventType, handler, [options], [callback])</span></span>

<span data-ttu-id="fc119-191">Добавляет обработчик для поддерживаемого события.</span><span class="sxs-lookup"><span data-stu-id="fc119-191">Adds an event handler for a supported event.</span></span>

<span data-ttu-id="fc119-192">В настоящее время, поддерживаемые типы событий, `Office.EventType.ItemChanged` и `Office.EventType.OfficeThemeChanged`.</span><span class="sxs-lookup"><span data-stu-id="fc119-192">Currently, the supported event types are `Office.EventType.ItemChanged` and `Office.EventType.OfficeThemeChanged`.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-193">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-193">Parameters:</span></span>

| <span data-ttu-id="fc119-194">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-194">Name</span></span> | <span data-ttu-id="fc119-195">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-195">Type</span></span> | <span data-ttu-id="fc119-196">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="fc119-196">Attributes</span></span> | <span data-ttu-id="fc119-197">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-197">Description</span></span> |
|---|---|---|---|
| `eventType` | [<span data-ttu-id="fc119-198">Office.EventType</span><span class="sxs-lookup"><span data-stu-id="fc119-198">Office.EventType</span></span>](office.md#eventtype-string) || <span data-ttu-id="fc119-199">Событие, которое должно вызвать обработчик.</span><span class="sxs-lookup"><span data-stu-id="fc119-199">The event that should invoke the handler.</span></span> |
| `handler` | <span data-ttu-id="fc119-200">Function</span><span class="sxs-lookup"><span data-stu-id="fc119-200">Function</span></span> || <span data-ttu-id="fc119-p106">Функция для обработки события. Функция должна принимать один параметр, представляющий собой объектный литерал. Значение свойства `type` параметра совпадет со значением параметра `eventType`, переданного методу `addHandlerAsync`.</span><span class="sxs-lookup"><span data-stu-id="fc119-p106">The function to handle the event. The function must accept a single parameter, which is an object literal. The `type` property on the parameter will match the `eventType` parameter passed to `addHandlerAsync`.</span></span> |
| `options` | <span data-ttu-id="fc119-204">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-204">Object</span></span> | <span data-ttu-id="fc119-205">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-205">&lt;optional&gt;</span></span> | <span data-ttu-id="fc119-206">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="fc119-206">An object literal that contains one or more of the following properties.</span></span> |
| `options.asyncContext` | <span data-ttu-id="fc119-207">Object</span><span class="sxs-lookup"><span data-stu-id="fc119-207">Object</span></span> | <span data-ttu-id="fc119-208">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-208">&lt;optional&gt;</span></span> | <span data-ttu-id="fc119-209">Разработчики могут указать любой объект, к которому необходимо получить доступ, в методе обратного вызова.</span><span class="sxs-lookup"><span data-stu-id="fc119-209">Developers can provide any object they wish to access in the callback method.</span></span> |
| `callback` | <span data-ttu-id="fc119-210">function</span><span class="sxs-lookup"><span data-stu-id="fc119-210">function</span></span>| <span data-ttu-id="fc119-211">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-211">&lt;optional&gt;</span></span>|<span data-ttu-id="fc119-212">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="fc119-212">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-213">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-213">Requirements</span></span>

|<span data-ttu-id="fc119-214">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-214">Requirement</span></span>| <span data-ttu-id="fc119-215">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-215">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-216">Минимальная версия набора обязательных элементов для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="fc119-216">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-217">1.5</span><span class="sxs-lookup"><span data-stu-id="fc119-217">1.5</span></span> |
|[<span data-ttu-id="fc119-218">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-218">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-219">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-219">ReadItem</span></span> |
|[<span data-ttu-id="fc119-220">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-220">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-221">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-221">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-222">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-222">Example</span></span>

```
Office.initialize = function (reason) {
  $(document).ready(function () {
    Office.context.mailbox.addHandlerAsync(Office.EventType.ItemChanged, loadNewItem, function (result) {
      if (result.status === Office.AsyncResultStatus.Failed) {
        // Handle error
      }
    });
  });
};

function loadNewItem(eventArgs) {
  // Load the properties of the newly selected item
  loadProps(Office.context.mailbox.item);
};
```

####  <a name="converttoewsiditemid-restversion--string"></a><span data-ttu-id="fc119-223">convertToEwsId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="fc119-223">convertToEwsId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="fc119-224">Преобразовывает идентификатор элемента из формата REST в формат EWS.</span><span class="sxs-lookup"><span data-stu-id="fc119-224">Converts an item ID formatted for REST into EWS format.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-225">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-225">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-p107">Формат идентификаторов, извлекаемых через API REST (например, [API Почты Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) или [Microsoft Graph](http://graph.microsoft.io/)), отличается от формата веб-служб Exchange (EWS). Метод `convertToEwsId` преобразовывает идентификатор в формате REST в формат EWS.</span><span class="sxs-lookup"><span data-stu-id="fc119-p107">Item IDs retrieved via a REST API (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)) use a different format than the format used by Exchange Web Services (EWS). The `convertToEwsId` method converts a REST-formatted ID into the proper format for EWS.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-228">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-228">Parameters:</span></span>

|<span data-ttu-id="fc119-229">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-229">Name</span></span>| <span data-ttu-id="fc119-230">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-230">Type</span></span>| <span data-ttu-id="fc119-231">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-231">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="fc119-232">String</span><span class="sxs-lookup"><span data-stu-id="fc119-232">String</span></span>|<span data-ttu-id="fc119-233">Идентификатор элемента в формате REST API для Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-233">An item ID formatted for the Outlook REST APIs</span></span>|
|`restVersion`| [<span data-ttu-id="fc119-234">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="fc119-234">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="fc119-235">Значение, определяющее версию REST API для Outlook, которая используется для извлечения идентификатора элемента.</span><span class="sxs-lookup"><span data-stu-id="fc119-235">A value indicating the version of the Outlook REST API used to retrieve the item ID.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-236">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-236">Requirements</span></span>

|<span data-ttu-id="fc119-237">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-237">Requirement</span></span>| <span data-ttu-id="fc119-238">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-238">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-239">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-239">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-240">1.3</span><span class="sxs-lookup"><span data-stu-id="fc119-240">1.3</span></span>|
|[<span data-ttu-id="fc119-241">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-241">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-242">Restricted</span><span class="sxs-lookup"><span data-stu-id="fc119-242">Restricted</span></span>|
|[<span data-ttu-id="fc119-243">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-243">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-244">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-244">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="fc119-245">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="fc119-245">Returns:</span></span>

<span data-ttu-id="fc119-246">Тип: String</span><span class="sxs-lookup"><span data-stu-id="fc119-246">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="fc119-247">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-247">Example</span></span>

```
// Get an item's ID from a REST API
var restId = 'AAMkAGVlOTZjNTM3LW...';

// Treat restId as coming from the v2.0 version of the
// Outlook Mail API
var ewsId = Office.context.mailbox.convertToEwsId(restId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime"></a><span data-ttu-id="fc119-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span><span class="sxs-lookup"><span data-stu-id="fc119-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span></span>

<span data-ttu-id="fc119-249">Получает словарь, содержащий сведения о локальном времени клиента.</span><span class="sxs-lookup"><span data-stu-id="fc119-249">Gets a dictionary containing time information in local client time.</span></span>

<span data-ttu-id="fc119-p108">В случае дат и времени в почтовом приложении для Outlook или Outlook Web App могут использоваться разные часовые пояса. Outlook использует часовой пояс клиентского компьютера. Outlook Web App использует часовой пояс, заданный в Центре администрирования Exchange (EAC). Значения даты и времени должны обрабатываться так, чтобы значения в пользовательском интерфейсе всегда согласовывались с часовым поясом, ожидаемым пользователем.</span><span class="sxs-lookup"><span data-stu-id="fc119-p108">The dates and times used by a mail app for Outlook or Outlook Web App can use different time zones. Outlook uses the client computer time zone; Outlook Web App uses the time zone set on the Exchange Admin Center (EAC). You should handle date and time values so that the values you display on the user interface are always consistent with the time zone that the user expects.</span></span>

<span data-ttu-id="fc119-p109">Если почтовое приложение работает в Outlook, метод `convertToLocalClientTime` вернет объект словаря со значениями часового пояса клиентского компьютера. Если почтовое приложение работает в Outlook Web App, метод `convertToLocalClientTime` вернет объект словаря со значениями часового пояса, заданного в Центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc119-p109">If the mail app is running in Outlook, the `convertToLocalClientTime` method will return a dictionary object with the values set to the client computer time zone. If the mail app is running in Outlook Web App, the `convertToLocalClientTime` method will return a dictionary object with the values set to the time zone specified in the EAC.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-255">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-255">Parameters:</span></span>

|<span data-ttu-id="fc119-256">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-256">Name</span></span>| <span data-ttu-id="fc119-257">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-257">Type</span></span>| <span data-ttu-id="fc119-258">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-258">Description</span></span>|
|---|---|---|
|`timeValue`| <span data-ttu-id="fc119-259">Date</span><span class="sxs-lookup"><span data-stu-id="fc119-259">Date</span></span>|<span data-ttu-id="fc119-260">Объект Date</span><span class="sxs-lookup"><span data-stu-id="fc119-260">A Date object</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-261">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-261">Requirements</span></span>

|<span data-ttu-id="fc119-262">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-262">Requirement</span></span>| <span data-ttu-id="fc119-263">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-263">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-264">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-264">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-265">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-265">1.0</span></span>|
|[<span data-ttu-id="fc119-266">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-266">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-267">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-267">ReadItem</span></span>|
|[<span data-ttu-id="fc119-268">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-268">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-269">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-269">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="fc119-270">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="fc119-270">Returns:</span></span>

<span data-ttu-id="fc119-271">Тип: [LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span><span class="sxs-lookup"><span data-stu-id="fc119-271">Type: [LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span></span>

####  <a name="converttorestiditemid-restversion--string"></a><span data-ttu-id="fc119-272">convertToRestId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="fc119-272">convertToRestId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="fc119-273">Преобразовывает идентификатор элемента в формате EWS в формат REST.</span><span class="sxs-lookup"><span data-stu-id="fc119-273">Converts an item ID formatted for EWS into REST format.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-274">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-274">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-p110">Формат идентификаторов, извлекаемых через EWS или свойство `itemId`, отличается от формата API REST (таких как [API Почты Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) или [Microsoft Graph](http://graph.microsoft.io/)). Метод `convertToRestId` преобразовывает идентификатор в формате EWS в формат REST.</span><span class="sxs-lookup"><span data-stu-id="fc119-p110">Item IDs retrieved via EWS or via the `itemId` property use a different format than the format used by REST APIs (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)). The `convertToRestId` method converts an EWS-formatted ID into the proper format for REST.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-277">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-277">Parameters:</span></span>

|<span data-ttu-id="fc119-278">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-278">Name</span></span>| <span data-ttu-id="fc119-279">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-279">Type</span></span>| <span data-ttu-id="fc119-280">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-280">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="fc119-281">String</span><span class="sxs-lookup"><span data-stu-id="fc119-281">String</span></span>|<span data-ttu-id="fc119-282">Идентификатор элемента в формате EWS</span><span class="sxs-lookup"><span data-stu-id="fc119-282">An item ID formatted for Exchange Web Services (EWS)</span></span>|
|`restVersion`| [<span data-ttu-id="fc119-283">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="fc119-283">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="fc119-284">Значение, определяющее версию REST API для Outlook, с которой будет использоваться преобразованный идентификатор.</span><span class="sxs-lookup"><span data-stu-id="fc119-284">A value indicating the version of the Outlook REST API that the converted ID will be used with.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-285">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-285">Requirements</span></span>

|<span data-ttu-id="fc119-286">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-286">Requirement</span></span>| <span data-ttu-id="fc119-287">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-287">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-288">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-288">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-289">1.3</span><span class="sxs-lookup"><span data-stu-id="fc119-289">1.3</span></span>|
|[<span data-ttu-id="fc119-290">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-290">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-291">Restricted</span><span class="sxs-lookup"><span data-stu-id="fc119-291">Restricted</span></span>|
|[<span data-ttu-id="fc119-292">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-292">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-293">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-293">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="fc119-294">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="fc119-294">Returns:</span></span>

<span data-ttu-id="fc119-295">Тип: String</span><span class="sxs-lookup"><span data-stu-id="fc119-295">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="fc119-296">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-296">Example</span></span>

```
// Get the currently selected item's ID
var ewsId = Office.context.mailbox.item.itemId;

// Convert to a REST ID for the v2.0 version of the
// Outlook Mail API
var restId = Office.context.mailbox.convertToRestId(ewsId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttoutcclienttimeinput--date"></a><span data-ttu-id="fc119-297">convertToUtcClientTime(input) → {Date}</span><span class="sxs-lookup"><span data-stu-id="fc119-297">convertToUtcClientTime(input) → {Date}</span></span>

<span data-ttu-id="fc119-298">Получает объект Date из словаря, содержащего сведения о времени.</span><span class="sxs-lookup"><span data-stu-id="fc119-298">Gets a Date object from a dictionary containing time information.</span></span>

<span data-ttu-id="fc119-299">Метод `convertToUtcClientTime` преобразует словарь, содержащий локальную дату и время, в объект Date с правильными значениями локальной даты и времени.</span><span class="sxs-lookup"><span data-stu-id="fc119-299">The `convertToUtcClientTime` method converts a dictionary containing a local date and time to a Date object with the correct values for the local date and time.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-300">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-300">Parameters:</span></span>

|<span data-ttu-id="fc119-301">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-301">Name</span></span>| <span data-ttu-id="fc119-302">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-302">Type</span></span>| <span data-ttu-id="fc119-303">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-303">Description</span></span>|
|---|---|---|
|`input`| [<span data-ttu-id="fc119-304">LocalClientTime</span><span class="sxs-lookup"><span data-stu-id="fc119-304">LocalClientTime</span></span>](/javascript/api/outlook/office.LocalClientTime)|<span data-ttu-id="fc119-305">Значение локального времени для преобразования.</span><span class="sxs-lookup"><span data-stu-id="fc119-305">The local time value to convert.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-306">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-306">Requirements</span></span>

|<span data-ttu-id="fc119-307">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-307">Requirement</span></span>| <span data-ttu-id="fc119-308">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-308">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-309">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-309">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-310">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-310">1.0</span></span>|
|[<span data-ttu-id="fc119-311">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-311">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-312">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-312">ReadItem</span></span>|
|[<span data-ttu-id="fc119-313">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-313">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-314">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-314">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="fc119-315">Возвращаемое значение:</span><span class="sxs-lookup"><span data-stu-id="fc119-315">Returns:</span></span>

<span data-ttu-id="fc119-316">Объект Date со временем в формате UTC.</span><span class="sxs-lookup"><span data-stu-id="fc119-316">A Date object with the time expressed in UTC.</span></span>

<dl class="param-type"><span data-ttu-id="fc119-317">

<dt>Тип</dt>

</span><span class="sxs-lookup"><span data-stu-id="fc119-317">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="fc119-318">Date</span><span class="sxs-lookup"><span data-stu-id="fc119-318">Date</span></span></dd>

</dl>

####  <a name="displayappointmentformitemid"></a><span data-ttu-id="fc119-319">displayAppointmentForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="fc119-319">displayAppointmentForm(itemId)</span></span>

<span data-ttu-id="fc119-320">Отображает имеющуюся встречу из календаря.</span><span class="sxs-lookup"><span data-stu-id="fc119-320">Displays an existing calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-321">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-321">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-322">Метод `displayAppointmentForm` открывает новое окно на компьютере или диалоговое окно на мобильном устройстве, содержащее сведения календаря о существующей встрече.</span><span class="sxs-lookup"><span data-stu-id="fc119-322">The `displayAppointmentForm` method opens an existing calendar appointment in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="fc119-p111">В Outlook для Mac с помощью этого метода можно отобразить одну встречу, которая не является частью повторяющегося ряда, или основную встречу такого ряда, но не экземпляр из него, так как в Outlook для Mac невозможно получить доступ к свойствам экземпляра повторяющегося ряда (в том числе к идентификатору элемента).</span><span class="sxs-lookup"><span data-stu-id="fc119-p111">In Outlook for Mac, you can use this method to display a single appointment that is not part of a recurring series, or the master appointment of a recurring series, but you cannot display an instance of the series. This is because in Outlook for Mac, you cannot access the properties (including the item ID) of instances of a recurring series.</span></span>

<span data-ttu-id="fc119-325">В Outlook Web App этот метод открывает указанную форму, только если текст формы содержит символы размером не более 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="fc119-325">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32KB number of characters.</span></span>

<span data-ttu-id="fc119-326">Если указанный идентификатор элемента не определяет существующую встречу, на клиентском компьютере или устройстве открывается пустая страница, и сообщение об ошибке не возвращается.</span><span class="sxs-lookup"><span data-stu-id="fc119-326">If the specified item identifier does not identify an existing appointment, a blank pane opens on the client computer or device, and no error message will be returned.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-327">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-327">Parameters:</span></span>

|<span data-ttu-id="fc119-328">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-328">Name</span></span>| <span data-ttu-id="fc119-329">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-329">Type</span></span>| <span data-ttu-id="fc119-330">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-330">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="fc119-331">String</span><span class="sxs-lookup"><span data-stu-id="fc119-331">String</span></span>|<span data-ttu-id="fc119-332">Идентификатор веб-служб Exchange для существующей встречи в календаре.</span><span class="sxs-lookup"><span data-stu-id="fc119-332">The Exchange Web Services (EWS) identifier for an existing calendar appointment.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-333">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-333">Requirements</span></span>

|<span data-ttu-id="fc119-334">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-334">Requirement</span></span>| <span data-ttu-id="fc119-335">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-335">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-336">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-336">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-337">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-337">1.0</span></span>|
|[<span data-ttu-id="fc119-338">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-338">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-339">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-339">ReadItem</span></span>|
|[<span data-ttu-id="fc119-340">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-340">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-341">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-341">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-342">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-342">Example</span></span>

```
Office.context.mailbox.displayAppointmentForm(appointmentId);
```

####  <a name="displaymessageformitemid"></a><span data-ttu-id="fc119-343">displayMessageForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="fc119-343">displayMessageForm(itemId)</span></span>

<span data-ttu-id="fc119-344">Отображает имеющееся сообщение.</span><span class="sxs-lookup"><span data-stu-id="fc119-344">Displays an existing message.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-345">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-345">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-346">Метод `displayMessageForm` открывает новое окно на компьютере или диалоговое окно на мобильном устройстве, содержащее существующее сообщение.</span><span class="sxs-lookup"><span data-stu-id="fc119-346">The `displayMessageForm` method opens an existing message in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="fc119-347">В Outlook Web App этот метод открывает указанную форму, только если текст формы содержит символы размером не более 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="fc119-347">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32 KB number of characters.</span></span>

<span data-ttu-id="fc119-348">Если указанный идентификатор элемента не определяет существующее сообщение, окно на клиентском компьютере не открывается и сообщение об ошибке не возвращается.</span><span class="sxs-lookup"><span data-stu-id="fc119-348">If the specified item identifier does not identify an existing message, no message will be displayed on the client computer, and no error message will be returned.</span></span>

<span data-ttu-id="fc119-p112">Не используйте `displayMessageForm` с параметром `itemId`, который представляет собой встречу. Используйте метод `displayAppointmentForm`, чтобы отобразить сведения о существующей встрече, а метод `displayNewAppointmentForm` — для отображения формы создания встречи.</span><span class="sxs-lookup"><span data-stu-id="fc119-p112">Do not use the `displayMessageForm` with an `itemId` that represents an appointment. Use the `displayAppointmentForm` method to display an existing appointment, and `displayNewAppointmentForm` to display a form to create a new appointment.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-351">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-351">Parameters:</span></span>

|<span data-ttu-id="fc119-352">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-352">Name</span></span>| <span data-ttu-id="fc119-353">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-353">Type</span></span>| <span data-ttu-id="fc119-354">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-354">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="fc119-355">String</span><span class="sxs-lookup"><span data-stu-id="fc119-355">String</span></span>|<span data-ttu-id="fc119-356">Идентификатор веб-служб Exchange для существующего сообщения.</span><span class="sxs-lookup"><span data-stu-id="fc119-356">The Exchange Web Services (EWS) identifier for an existing message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-357">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-357">Requirements</span></span>

|<span data-ttu-id="fc119-358">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-358">Requirement</span></span>| <span data-ttu-id="fc119-359">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-359">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-360">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-360">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-361">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-361">1.0</span></span>|
|[<span data-ttu-id="fc119-362">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-362">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-363">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-363">ReadItem</span></span>|
|[<span data-ttu-id="fc119-364">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-364">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-365">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-365">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-366">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-366">Example</span></span>

```
Office.context.mailbox.displayMessageForm(messageId);
```

#### <a name="displaynewappointmentformparameters"></a><span data-ttu-id="fc119-367">displayNewAppointmentForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="fc119-367">displayNewAppointmentForm(parameters)</span></span>

<span data-ttu-id="fc119-368">Отображает форму для создания новой встречи в календаре.</span><span class="sxs-lookup"><span data-stu-id="fc119-368">Displays a form for creating a new calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-369">Этот метод не поддерживается в Outlook для операций ввода-вывода или Outlook для Android.</span><span class="sxs-lookup"><span data-stu-id="fc119-369">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="fc119-p113">Метод `displayNewAppointmentForm` открывает форму, в которой пользователь может создать встречу или собрание. Если параметры заданы, поля формы встречи автоматически заполняются их содержимым.</span><span class="sxs-lookup"><span data-stu-id="fc119-p113">The `displayNewAppointmentForm` method opens a form that enables the user to create a new appointment or meeting. If parameters are specified, the appointment form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="fc119-p114">В Outlook Web App и Outlook Web App для устройств этот метод всегда отображает форму с полем участников. Если вы не укажете участников в качестве входных аргументов, метод отображает форму с кнопкой **Сохранить**. Если вы укажете участников, форма будет включать участников и кнопку **Отправить**.</span><span class="sxs-lookup"><span data-stu-id="fc119-p114">In Outlook Web App and OWA for Devices, this method always displays a form with an attendees field. If you do not specify any attendees as input arguments, the method displays a form with a **Save** button. If you have specified attendees, the form would include the attendees and a **Send** button.</span></span>

<span data-ttu-id="fc119-p115">Если вы укажете участников или ресурсы с помощью параметра `requiredAttendees`, `optionalAttendees` или `resources` в клиенте Outlook с расширенными возможностями и Outlook RT, этот метод отобразит форму собрания с кнопкой **Отправить**. Если не указать получателей, этот метод отобразит форму встречи с кнопкой **Сохранить и закрыть**.</span><span class="sxs-lookup"><span data-stu-id="fc119-p115">In the Outlook rich client and Outlook RT, if you specify any attendees or resources in the `requiredAttendees`, `optionalAttendees`, or `resources` parameter, this method displays a meeting form with a **Send** button. If you don't specify any recipients, this method displays an appointment form with a **Save & Close** button.</span></span>

<span data-ttu-id="fc119-377">Если параметры превышают указанные ограничения размера или если указано неизвестное имя параметра, вызывается исключение.</span><span class="sxs-lookup"><span data-stu-id="fc119-377">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-378">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-378">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-379">Все параметры являются необязательными.</span><span class="sxs-lookup"><span data-stu-id="fc119-379">All parameters are optional.</span></span>

|<span data-ttu-id="fc119-380">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-380">Name</span></span>| <span data-ttu-id="fc119-381">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-381">Type</span></span>| <span data-ttu-id="fc119-382">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-382">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="fc119-383">Object</span><span class="sxs-lookup"><span data-stu-id="fc119-383">Object</span></span> | <span data-ttu-id="fc119-384">Словарь параметров, описывающий новую встречу.</span><span class="sxs-lookup"><span data-stu-id="fc119-384">A dictionary of parameters describing the new appointment.</span></span> |
| `parameters.requiredAttendees` | <span data-ttu-id="fc119-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="fc119-p116">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из обязательных участников встречи. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-p116">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the required attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.optionalAttendees` | <span data-ttu-id="fc119-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="fc119-p117">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из необязательных участников встречи. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-p117">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the optional attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.start` | <span data-ttu-id="fc119-391">Date</span><span class="sxs-lookup"><span data-stu-id="fc119-391">Date</span></span> | <span data-ttu-id="fc119-392">Объект `Date`, указывающий дату и время начала встречи.</span><span class="sxs-lookup"><span data-stu-id="fc119-392">A `Date` object specifying the start date and time of the appointment.</span></span> |
| `parameters.end` | <span data-ttu-id="fc119-393">Date</span><span class="sxs-lookup"><span data-stu-id="fc119-393">Date</span></span> | <span data-ttu-id="fc119-394">Объект `Date`, указывающий дату и время окончания встречи.</span><span class="sxs-lookup"><span data-stu-id="fc119-394">A `Date` object specifying the end date and time of the appointment.</span></span> |
| `parameters.location` | <span data-ttu-id="fc119-395">String</span><span class="sxs-lookup"><span data-stu-id="fc119-395">String</span></span> | <span data-ttu-id="fc119-p118">Строка со сведениями о месте встречи. Максимальное количество символов в строке — 255.</span><span class="sxs-lookup"><span data-stu-id="fc119-p118">A string containing the location of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.resources` | <span data-ttu-id="fc119-398">Array.&lt;String&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-398">Array.&lt;String&gt;</span></span> | <span data-ttu-id="fc119-p119">Массив строк, содержащий необходимые для встречи ресурсы. Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-p119">An array of strings containing the resources required for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="fc119-401">String</span><span class="sxs-lookup"><span data-stu-id="fc119-401">String</span></span> | <span data-ttu-id="fc119-p120">Строка с темой встречи. Максимальное количество символов в строке — 255.</span><span class="sxs-lookup"><span data-stu-id="fc119-p120">A string containing the subject of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.body` | <span data-ttu-id="fc119-404">String</span><span class="sxs-lookup"><span data-stu-id="fc119-404">String</span></span> | <span data-ttu-id="fc119-p121">Текст сообщения о встрече. Максимальный размер содержимого сообщения — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="fc119-p121">The body of the appointment. The body content is limited to a maximum size of 32 KB.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="fc119-407">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-407">Requirements</span></span>

|<span data-ttu-id="fc119-408">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-408">Requirement</span></span>| <span data-ttu-id="fc119-409">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-409">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-410">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-410">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-411">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-411">1.0</span></span>|
|[<span data-ttu-id="fc119-412">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-412">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-413">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-413">ReadItem</span></span>|
|[<span data-ttu-id="fc119-414">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-414">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-415">Чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-415">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-416">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-416">Example</span></span>

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

#### <a name="displaynewmessageformparameters"></a><span data-ttu-id="fc119-417">displayNewMessageForm(параметры)</span><span class="sxs-lookup"><span data-stu-id="fc119-417">displayNewMessageForm(parameters)</span></span>

<span data-ttu-id="fc119-418">Отображает форму для создания сообщения.</span><span class="sxs-lookup"><span data-stu-id="fc119-418">Displays a form for creating a new message.</span></span>

<span data-ttu-id="fc119-419">Метод `displayNewMessageForm` открывает форму, в которой пользователь может создать сообщение.</span><span class="sxs-lookup"><span data-stu-id="fc119-419">The `displayNewMessageForm` method opens a form that enables the user to create a new message.</span></span> <span data-ttu-id="fc119-420">Если параметры заданы, поля формы сообщения автоматически заполняются их содержимым.</span><span class="sxs-lookup"><span data-stu-id="fc119-420">If parameters are specified, the message form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="fc119-421">Если параметры превышают указанные ограничения размера или если указано неизвестное имя параметра, вызывается исключение.</span><span class="sxs-lookup"><span data-stu-id="fc119-421">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-422">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-422">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-423">Все параметры являются необязательными.</span><span class="sxs-lookup"><span data-stu-id="fc119-423">All parameters are optional.</span></span>

|<span data-ttu-id="fc119-424">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-424">Name</span></span>| <span data-ttu-id="fc119-425">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-425">Type</span></span>| <span data-ttu-id="fc119-426">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-426">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="fc119-427">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-427">Object</span></span> | <span data-ttu-id="fc119-428">Словарь параметров, описывающий новое сообщение.</span><span class="sxs-lookup"><span data-stu-id="fc119-428">A dictionary of parameters describing the new message.</span></span> |
| `parameters.toRecipients` | <span data-ttu-id="fc119-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="fc119-430">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из получателей, указанных в строке "Кому".</span><span class="sxs-lookup"><span data-stu-id="fc119-430">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the To line.</span></span> <span data-ttu-id="fc119-431">Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-431">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.ccRecipients` | <span data-ttu-id="fc119-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="fc119-433">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из получателей, указанных в строке "Копия".</span><span class="sxs-lookup"><span data-stu-id="fc119-433">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Cc line.</span></span> <span data-ttu-id="fc119-434">Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-434">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.bccRecipients` | <span data-ttu-id="fc119-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="fc119-436">Массив строк, содержащий электронные адреса, или массив, содержащий объекты `EmailAddressDetails` для каждого из получателей, указанных в строке "Скрытая копия".</span><span class="sxs-lookup"><span data-stu-id="fc119-436">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Bcc line.</span></span> <span data-ttu-id="fc119-437">Массив может включать не более 100 записей.</span><span class="sxs-lookup"><span data-stu-id="fc119-437">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="fc119-438">String</span><span class="sxs-lookup"><span data-stu-id="fc119-438">String</span></span> | <span data-ttu-id="fc119-439">Строка с темой сообщения.</span><span class="sxs-lookup"><span data-stu-id="fc119-439">A string containing the subject of the message.</span></span> <span data-ttu-id="fc119-440">Максимальное количество символов в строке — 255.</span><span class="sxs-lookup"><span data-stu-id="fc119-440">The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.htmlBody` | <span data-ttu-id="fc119-441">String</span><span class="sxs-lookup"><span data-stu-id="fc119-441">String</span></span> | <span data-ttu-id="fc119-442">Текст сообщения в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="fc119-442">The HTML body of the message.</span></span> <span data-ttu-id="fc119-443">Максимальный размер содержимого сообщения — 32 КБ.</span><span class="sxs-lookup"><span data-stu-id="fc119-443">The body content is limited to a maximum size of 32 KB.</span></span> |
| `parameters.attachments` | <span data-ttu-id="fc119-444">Array.&lt;Object&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-444">Array.&lt;Object&gt;</span></span> | <span data-ttu-id="fc119-445">Массив объектов JSON, представляющих собой вложенные файлы или элементы.</span><span class="sxs-lookup"><span data-stu-id="fc119-445">An array of JSON objects that are either file or item attachments.</span></span> |
| `parameters.attachments.type` | <span data-ttu-id="fc119-446">String</span><span class="sxs-lookup"><span data-stu-id="fc119-446">String</span></span> | <span data-ttu-id="fc119-p128">Указывает тип вложения. Допустимые значения: `file` для вложенного файла и `item` для вложенного элемента.</span><span class="sxs-lookup"><span data-stu-id="fc119-p128">Indicates the type of attachment. Must be `file` for a file attachment or `item` for an item attachment.</span></span> |
| `parameters.attachments.name` | <span data-ttu-id="fc119-449">String</span><span class="sxs-lookup"><span data-stu-id="fc119-449">String</span></span> | <span data-ttu-id="fc119-450">Строка, содержащая имя вложения, длиной до 255 символов.</span><span class="sxs-lookup"><span data-stu-id="fc119-450">A string that contains the name of the attachment, up to 255 characters in length.</span></span>|
| `parameters.attachments.url` | <span data-ttu-id="fc119-451">String</span><span class="sxs-lookup"><span data-stu-id="fc119-451">String</span></span> | <span data-ttu-id="fc119-p129">Используется, только если свойству `type` задано значение `file`. URI расположения файла.</span><span class="sxs-lookup"><span data-stu-id="fc119-p129">Only used if `type` is set to `file`. The URI of the location for the file.</span></span> |
| `parameters.attachments.isInline` | <span data-ttu-id="fc119-454">Boolean</span><span class="sxs-lookup"><span data-stu-id="fc119-454">Boolean</span></span> | <span data-ttu-id="fc119-p130">Используется, только если свойству `type` задано значение `file`. Значение `true` указывает на то, что вложение будет встроено в текст сообщения и не должно отображаться в списке вложений.</span><span class="sxs-lookup"><span data-stu-id="fc119-p130">Only used if `type` is set to `file`. If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
| `parameters.attachments.itemId` | <span data-ttu-id="fc119-457">String</span><span class="sxs-lookup"><span data-stu-id="fc119-457">String</span></span> | <span data-ttu-id="fc119-458">Используется, только если свойству `type` присвоено значение `item`.</span><span class="sxs-lookup"><span data-stu-id="fc119-458">Only used if `type` is set to `item`.</span></span> <span data-ttu-id="fc119-459">Идентификатор элемента веб-служб Exchange существующего сообщения электронной почты, которые необходимо присоединить к новое сообщение.</span><span class="sxs-lookup"><span data-stu-id="fc119-459">The EWS item id of the existing e-mail you want to attach to the new message.</span></span> <span data-ttu-id="fc119-460">Это строка длиной до 100 символов.</span><span class="sxs-lookup"><span data-stu-id="fc119-460">This is a string up to 100 characters.</span></span> |


##### <a name="requirements"></a><span data-ttu-id="fc119-461">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-461">Requirements</span></span>

|<span data-ttu-id="fc119-462">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-462">Requirement</span></span>| <span data-ttu-id="fc119-463">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-463">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-464">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-464">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-465">1.6</span><span class="sxs-lookup"><span data-stu-id="fc119-465">1.6</span></span> |
|[<span data-ttu-id="fc119-466">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-466">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-467">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-467">ReadItem</span></span>|
|[<span data-ttu-id="fc119-468">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-468">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-469">Чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-469">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-470">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-470">Example</span></span>

```
Office.context.mailbox.displayNewMessageForm(
  {
    toRecipients: Office.context.mailbox.item.to, // Copy the To line from current item
    ccRecipients: ['sam@contoso.com'],
    subject: 'Outlook add-ins are cool!',
    htmlBody: 'Hello <b>World</b>!<br/><img src="cid:image.png"></i>',
    attachments: [
      {
        type: 'file',
        name: 'image.png',
        url: 'http://contoso.com/image.png',
        isInline: true
      }
    ]
  });
```

#### <a name="getcallbacktokenasyncoptions-callback"></a><span data-ttu-id="fc119-471">getCallbackTokenAsync([options], callback)</span><span class="sxs-lookup"><span data-stu-id="fc119-471">getCallbackTokenAsync([options], callback)</span></span>

<span data-ttu-id="fc119-472">Возвращает строку, содержащую маркер, который используется для вызова интерфейсов REST API или веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc119-472">Gets a string that contains a token used to call REST APIs or Exchange Web Services.</span></span>

<span data-ttu-id="fc119-p132">Метод `getCallbackTokenAsync` совершает асинхронный вызов, чтобы получить непрозрачный токен с сервера Exchange Server, на котором размещен почтовый ящик пользователя. Время существования маркера обратного вызова составляет 5 минут.</span><span class="sxs-lookup"><span data-stu-id="fc119-p132">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-475">Рекомендуется использовать, что надстройки API-интерфейсы REST вместо веб-служб Exchange по возможности.</span><span class="sxs-lookup"><span data-stu-id="fc119-475">It is recommended that add-ins use the REST APIs instead of Exchange Web Services whenever possible.</span></span> 

<span data-ttu-id="fc119-476">**Маркеры REST**</span><span class="sxs-lookup"><span data-stu-id="fc119-476">**REST Tokens**</span></span>

<span data-ttu-id="fc119-p133">Если запрашивается маркер REST (`options.isRest = true`), полученный маркер не подойдет для проверки подлинности при вызовах веб-служб Exchange. Область действия маркера будет ограничена доступом только для чтения к текущему элементу и его вложениям, если в манифесте надстройки не указано разрешение [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission). Если указано разрешение `ReadWriteMailbox`, полученный маркер предоставит доступ на чтение и запись к почте, календарю и контактам, включая возможность отправки почты.</span><span class="sxs-lookup"><span data-stu-id="fc119-p133">When a REST token is requested (`options.isRest = true`), the resulting token will not work to authenticate Exchange Web Services calls. The token will be limited in scope to read-only access to the current item and its attachments, unless the add-in has specified the [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) permission in its manifest. If the `ReadWriteMailbox` permission is specified, the resulting token will grant read/write access to mail, calendar, and contacts, including the ability to send mail.</span></span>

<span data-ttu-id="fc119-480">С помощью свойства `restUrl` надстройка должна определить правильный URL-адрес для вызовов REST API.</span><span class="sxs-lookup"><span data-stu-id="fc119-480">The add-in should use the `restUrl` property to determine the correct URL to use when making REST API calls.</span></span>

<span data-ttu-id="fc119-481">**Маркеры EWS**</span><span class="sxs-lookup"><span data-stu-id="fc119-481">**EWS Tokens**</span></span>

<span data-ttu-id="fc119-p134">Если запрашивается маркер EWS (`options.isRest = false`), полученный маркер не подойдет для проверки подлинности при вызовах REST API. Область действия маркера будет ограничена доступом к текущему элементу.</span><span class="sxs-lookup"><span data-stu-id="fc119-p134">When an EWS token is requested (`options.isRest = false`), the resulting token will not work to authenticate REST API calls. The token will be limited in scope to accessing the current item.</span></span>

<span data-ttu-id="fc119-484">С помощью свойства `ewsUrl` надстройка должна определить правильный URL-адрес для вызовов EWS.</span><span class="sxs-lookup"><span data-stu-id="fc119-484">The add-in should use the `ewsUrl` property to determine the correct URL to use when making EWS calls.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-485">Параметры:</span><span class="sxs-lookup"><span data-stu-id="fc119-485">Parameters:</span></span>

|<span data-ttu-id="fc119-486">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-486">Name</span></span>| <span data-ttu-id="fc119-487">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-487">Type</span></span>| <span data-ttu-id="fc119-488">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="fc119-488">Attributes</span></span>| <span data-ttu-id="fc119-489">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-489">Description</span></span>|
|---|---|---|---|
| `options` | <span data-ttu-id="fc119-490">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-490">Object</span></span> | <span data-ttu-id="fc119-491">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-491">&lt;optional&gt;</span></span> | <span data-ttu-id="fc119-492">Объектный литерал, содержащий одно или несколько из указанных ниже свойств.</span><span class="sxs-lookup"><span data-stu-id="fc119-492">An object literal that contains one or more of the following properties.</span></span> |
| `options.isRest` | <span data-ttu-id="fc119-493">Boolean</span><span class="sxs-lookup"><span data-stu-id="fc119-493">Boolean</span></span> |  <span data-ttu-id="fc119-494">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-494">&lt;optional&gt;</span></span> | <span data-ttu-id="fc119-p135">Определяет, будет ли предоставленный маркер использоваться для интерфейсов REST API Outlook или веб-служб Exchange. Значение по умолчанию: `false`.</span><span class="sxs-lookup"><span data-stu-id="fc119-p135">Determines if the token provided will be used for the Outlook REST APIs or Exchange Web Services. Default value is `false`.</span></span> |
| `options.asyncContext` | <span data-ttu-id="fc119-497">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-497">Object</span></span> |  <span data-ttu-id="fc119-498">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-498">&lt;optional&gt;</span></span> | <span data-ttu-id="fc119-499">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="fc119-499">Any state data that is passed to the asynchronous method.</span></span> |
|`callback`| <span data-ttu-id="fc119-500">function</span><span class="sxs-lookup"><span data-stu-id="fc119-500">function</span></span>||<span data-ttu-id="fc119-p136">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult). Токен указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="fc119-p136">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-503">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-503">Requirements</span></span>

|<span data-ttu-id="fc119-504">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-504">Requirement</span></span>| <span data-ttu-id="fc119-505">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-505">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-506">Минимальная версия набора обязательных элементов для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="fc119-506">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-507">1.5</span><span class="sxs-lookup"><span data-stu-id="fc119-507">1.5</span></span> |
|[<span data-ttu-id="fc119-508">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-508">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-509">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-509">ReadItem</span></span>|
|[<span data-ttu-id="fc119-510">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-510">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-511">Создание и чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-511">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-512">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-512">Example</span></span>

```js
function getCallbackToken() {
  var options = {
    isRest: true,
    asyncContext: { message: 'Hello World!' }
  };

  Office.context.mailbox.getCallbackTokenAsync(options, cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

#### <a name="getcallbacktokenasynccallback-usercontext"></a><span data-ttu-id="fc119-513">getCallbackTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="fc119-513">getCallbackTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="fc119-514">Получает строку, содержащую маркер, используемый для получения вложения или элемента с Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="fc119-514">Gets a string that contains a token used to get an attachment or item from an Exchange Server.</span></span>

<span data-ttu-id="fc119-p137">Метод `getCallbackTokenAsync` совершает асинхронный вызов, чтобы получить непрозрачный токен с сервера Exchange Server, на котором размещен почтовый ящик пользователя. Время существования маркера обратного вызова составляет 5 минут.</span><span class="sxs-lookup"><span data-stu-id="fc119-p137">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

<span data-ttu-id="fc119-p138">Вы можете передать сторонней системе токен и идентификатор вложения или элемента. Сторонняя система использует этот токен как токен авторизации, чтобы вызвать операцию [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) или [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) веб-служб Exchange для возврата вложения или элемента. Например, вы можете создать удаленную службу, чтобы [получить вложения из выбранного элемента](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="fc119-p138">You can pass the token and an attachment identifier or item identifier to a third-party system. The third-party system uses the token as a bearer authorization token to call the Exchange Web Services (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) or [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) operation to return an attachment or item. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="fc119-520">Для вызова метода `getCallbackTokenAsync` в режиме чтения манифесте приложения должно быть указано разрешение **ReadItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-520">Your app must have the **ReadItem** permission specified in its manifest to call the `getCallbackTokenAsync` method in read mode.</span></span>

<span data-ttu-id="fc119-p139">Чтобы получить идентификатор элемента для передачи в метод `getCallbackTokenAsync`, в режиме создания необходимо вызвать метод [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback). Для вызова метода `saveAsync` приложение должно иметь разрешения **ReadWriteItem**.</span><span class="sxs-lookup"><span data-stu-id="fc119-p139">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method to get an item identifier to pass to the `getCallbackTokenAsync` method. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-523">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-523">Parameters:</span></span>

|<span data-ttu-id="fc119-524">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-524">Name</span></span>| <span data-ttu-id="fc119-525">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-525">Type</span></span>| <span data-ttu-id="fc119-526">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="fc119-526">Attributes</span></span>| <span data-ttu-id="fc119-527">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-527">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="fc119-528">function</span><span class="sxs-lookup"><span data-stu-id="fc119-528">function</span></span>||<span data-ttu-id="fc119-p140">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult). Токен указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="fc119-p140">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="fc119-531">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-531">Object</span></span>| <span data-ttu-id="fc119-532">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-532">&lt;optional&gt;</span></span>|<span data-ttu-id="fc119-533">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="fc119-533">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-534">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-534">Requirements</span></span>

|<span data-ttu-id="fc119-535">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-535">Requirement</span></span>| <span data-ttu-id="fc119-536">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-536">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-537">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-537">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-538">1.3</span><span class="sxs-lookup"><span data-stu-id="fc119-538">1.3</span></span>|
|[<span data-ttu-id="fc119-539">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-539">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-540">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-540">ReadItem</span></span>|
|[<span data-ttu-id="fc119-541">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-541">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-542">Создание и чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-542">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-543">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-543">Example</span></span>

```js
function getCallbackToken() {
  Office.context.mailbox.getCallbackTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="getuseridentitytokenasynccallback-usercontext"></a><span data-ttu-id="fc119-544">getUserIdentityTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="fc119-544">getUserIdentityTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="fc119-545">Получает маркер, идентифицирующий пользователя и надстройку Office.</span><span class="sxs-lookup"><span data-stu-id="fc119-545">Gets a token identifying the user and the Office Add-in.</span></span>

<span data-ttu-id="fc119-546">Метод `getUserIdentityTokenAsync` возвращает токен, который можно использовать для идентификации, а также [проверки подлинности надстройки и пользователя в сторонней системе](https://docs.microsoft.com/outlook/add-ins/authentication).</span><span class="sxs-lookup"><span data-stu-id="fc119-546">The `getUserIdentityTokenAsync` method returns a token that you can use to identify and [authenticate the add-in and user with a third-party system](https://docs.microsoft.com/outlook/add-ins/authentication).</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-547">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-547">Parameters:</span></span>

|<span data-ttu-id="fc119-548">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-548">Name</span></span>| <span data-ttu-id="fc119-549">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-549">Type</span></span>| <span data-ttu-id="fc119-550">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="fc119-550">Attributes</span></span>| <span data-ttu-id="fc119-551">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-551">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="fc119-552">function</span><span class="sxs-lookup"><span data-stu-id="fc119-552">function</span></span>||<span data-ttu-id="fc119-553">После выполнения метода функция, переданная в параметре `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="fc119-553">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="fc119-554">Токен указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="fc119-554">The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="fc119-555">Object</span><span class="sxs-lookup"><span data-stu-id="fc119-555">Object</span></span>| <span data-ttu-id="fc119-556">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-556">&lt;optional&gt;</span></span>|<span data-ttu-id="fc119-557">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="fc119-557">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-558">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-558">Requirements</span></span>

|<span data-ttu-id="fc119-559">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-559">Requirement</span></span>| <span data-ttu-id="fc119-560">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-560">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-561">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-561">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-562">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-562">1.0</span></span>|
|[<span data-ttu-id="fc119-563">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-563">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-564">ReadItem</span><span class="sxs-lookup"><span data-stu-id="fc119-564">ReadItem</span></span>|
|[<span data-ttu-id="fc119-565">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-565">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-566">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-566">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-567">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-567">Example</span></span>

```js
function getIdentityToken() {
  Office.context.mailbox.getUserIdentityTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="makeewsrequestasyncdata-callback-usercontext"></a><span data-ttu-id="fc119-568">makeEwsRequestAsync(data, callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="fc119-568">makeEwsRequestAsync(data, callback, [userContext])</span></span>

<span data-ttu-id="fc119-569">Выполняет асинхронный запрос для веб-служб Exchange (EWS) на сервере Exchange Server, на котором размещен почтовый ящик пользователя.</span><span class="sxs-lookup"><span data-stu-id="fc119-569">Makes an asynchronous request to an Exchange Web Services (EWS) service on the Exchange server that hosts the user’s mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-570">Этот метод не поддерживается в следующих случаях.</span><span class="sxs-lookup"><span data-stu-id="fc119-570">This method is not supported in the following scenarios.</span></span>
> - <span data-ttu-id="fc119-571">В Outlook для операций ввода-вывода или Outlook для Android (en)</span><span class="sxs-lookup"><span data-stu-id="fc119-571">In Outlook for iOS or Outlook for Android</span></span>
> - <span data-ttu-id="fc119-572">Когда надстройки загружается в почтовом ящике Gmail</span><span class="sxs-lookup"><span data-stu-id="fc119-572">When the add-in is loaded in a Gmail mailbox</span></span>
> 
> <span data-ttu-id="fc119-573">В таких случаях надстроек следует [использовать API -интерфейсы REST](https://docs.microsoft.com/outlook/add-ins/use-rest-api) к почтового ящика пользователя.</span><span class="sxs-lookup"><span data-stu-id="fc119-573">In these cases, add-ins should [use REST APIs](https://docs.microsoft.com/outlook/add-ins/use-rest-api) to access the user's mailbox instead.</span></span>

<span data-ttu-id="fc119-574">Метод `makeEwsRequestAsync` отправляет запрос EWS от имени надстройки в Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc119-574">The `makeEwsRequestAsync` method sends an EWS request on behalf of the add-in to Exchange.</span></span> <span data-ttu-id="fc119-575">[Вызов веб-служб из надстройки Outlook](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) в разделе список поддерживаемые операции веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc119-575">See [Call web services from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) for a list of the supported EWS operations.</span></span>

<span data-ttu-id="fc119-576">С помощью метода `makeEwsRequestAsync` невозможно запрашивать элементы, связанные с папкой.</span><span class="sxs-lookup"><span data-stu-id="fc119-576">You cannot request Folder Associated Items with the `makeEwsRequestAsync` method.</span></span>

<span data-ttu-id="fc119-577">В запросе XML должна быть указана кодировка UTF-8.</span><span class="sxs-lookup"><span data-stu-id="fc119-577">The XML request must specify UTF-8 encoding.</span></span>

```
<?xml version="1.0" encoding="utf-8"?>
```

<span data-ttu-id="fc119-p142">У вашей надстройки должно быть разрешение **ReadWriteMailbox** для использования метода `makeEwsRequestAsync`. Сведения об использовании разрешения **ReadWriteMailbox** и операций EWS, которые можно вызывать с помощью метода `makeEwsRequestAsync`, см. в статье [Указание разрешений для доступа почтовой надстройки к почтовому ящику пользователя](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span><span class="sxs-lookup"><span data-stu-id="fc119-p142">Your add-in must have the **ReadWriteMailbox** permission to use the `makeEwsRequestAsync` method. For information about using the **ReadWriteMailbox** permission and the EWS operations that you can call with the `makeEwsRequestAsync` method, see [Specify permissions for mail add-in access to the user's mailbox](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span></span>

> [!NOTE]
> <span data-ttu-id="fc119-580">Администратор сервера должен установить `OAuthAuthentication` имеет значение true в каталоге Client Access Server EWS, чтобы включить `makeEwsRequestAsync` запрашивает метод веб-служб Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc119-580">The server administrator must set `OAuthAuthentication` to true on the Client Access Server EWS directory to enable the `makeEwsRequestAsync` method to make EWS requests.</span></span>

##### <a name="version-differences"></a><span data-ttu-id="fc119-581">Различия версий</span><span class="sxs-lookup"><span data-stu-id="fc119-581">Version differences</span></span>

<span data-ttu-id="fc119-582">Если вы используете метод `makeEwsRequestAsync` в почтовых приложениях, которые выполняются в Outlook версии более ранней, чем 15.0.4535.1004, указывайте кодировку `ISO-8859-1`.</span><span class="sxs-lookup"><span data-stu-id="fc119-582">When you use the `makeEwsRequestAsync` method in mail apps running in Outlook versions earlier than version 15.0.4535.1004, you should set the encoding value to `ISO-8859-1`.</span></span>

```
<?xml version="1.0" encoding="iso-8859-1"?>
```

<span data-ttu-id="fc119-p143">Значение кодировки не нужно указывать, если почтовое приложение выполняется в Outlook в Интернете. Чтобы определить, выполняется ли приложение в Outlook или Outlook в Интернете, используйте свойство mailbox.diagnostics.hostName. Используемую версию Outlook можно определить с помощью свойства mailbox.diagnostics.hostVersion.</span><span class="sxs-lookup"><span data-stu-id="fc119-p143">You do not need to set the encoding value when your mail app is running in Outlook on the web. You can determine whether your mail app is running in Outlook or Outlook on the web by using the mailbox.diagnostics.hostName property. You can determine what version of Outlook is running by using the mailbox.diagnostics.hostVersion property.</span></span>

##### <a name="parameters"></a><span data-ttu-id="fc119-586">Параметры</span><span class="sxs-lookup"><span data-stu-id="fc119-586">Parameters:</span></span>

|<span data-ttu-id="fc119-587">Имя</span><span class="sxs-lookup"><span data-stu-id="fc119-587">Name</span></span>| <span data-ttu-id="fc119-588">Тип</span><span class="sxs-lookup"><span data-stu-id="fc119-588">Type</span></span>| <span data-ttu-id="fc119-589">Атрибуты</span><span class="sxs-lookup"><span data-stu-id="fc119-589">Attributes</span></span>| <span data-ttu-id="fc119-590">Описание</span><span class="sxs-lookup"><span data-stu-id="fc119-590">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="fc119-591">String</span><span class="sxs-lookup"><span data-stu-id="fc119-591">String</span></span>||<span data-ttu-id="fc119-592">Запрос EWS.</span><span class="sxs-lookup"><span data-stu-id="fc119-592">The EWS request.</span></span>|
|`callback`| <span data-ttu-id="fc119-593">function</span><span class="sxs-lookup"><span data-stu-id="fc119-593">function</span></span>||<span data-ttu-id="fc119-594">После применения метода функция, переданная в параметр `callback`, вызывается с помощью параметра `asyncResult`, который представляет собой объект [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="fc119-594">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="fc119-595">Результат XML вызова EWS указывается в виде строки в свойстве `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="fc119-595">The XML result of the EWS call is provided as a string in the `asyncResult.value` property.</span></span> <span data-ttu-id="fc119-596">Если результат превышает 1 МБ по размеру, возвращается сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="fc119-596">If the result exceeds 1 MB in size, an error message is returned instead.</span></span>|
|`userContext`| <span data-ttu-id="fc119-597">Объект</span><span class="sxs-lookup"><span data-stu-id="fc119-597">Object</span></span>| <span data-ttu-id="fc119-598">&lt;необязательно&gt;</span><span class="sxs-lookup"><span data-stu-id="fc119-598">&lt;optional&gt;</span></span>|<span data-ttu-id="fc119-599">Данные о состоянии, передаваемые в асинхронный метод.</span><span class="sxs-lookup"><span data-stu-id="fc119-599">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="fc119-600">Требования</span><span class="sxs-lookup"><span data-stu-id="fc119-600">Requirements</span></span>

|<span data-ttu-id="fc119-601">Requirement</span><span class="sxs-lookup"><span data-stu-id="fc119-601">Requirement</span></span>| <span data-ttu-id="fc119-602">Значение</span><span class="sxs-lookup"><span data-stu-id="fc119-602">Value</span></span>|
|---|---|
|[<span data-ttu-id="fc119-603">Версия минимального набора требований к почтовому ящику</span><span class="sxs-lookup"><span data-stu-id="fc119-603">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="fc119-604">1.0</span><span class="sxs-lookup"><span data-stu-id="fc119-604">1.0</span></span>|
|[<span data-ttu-id="fc119-605">Минимальный уровень разрешений</span><span class="sxs-lookup"><span data-stu-id="fc119-605">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="fc119-606">ReadWriteMailbox</span><span class="sxs-lookup"><span data-stu-id="fc119-606">ReadWriteMailbox</span></span>|
|[<span data-ttu-id="fc119-607">Применимый режим Outlook</span><span class="sxs-lookup"><span data-stu-id="fc119-607">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="fc119-608">Создание или чтение</span><span class="sxs-lookup"><span data-stu-id="fc119-608">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="fc119-609">Пример</span><span class="sxs-lookup"><span data-stu-id="fc119-609">Example</span></span>

<span data-ttu-id="fc119-610">В следующем примере вызывается `makeEwsRequestAsync` для получения темы элемента с помощью операции `GetItem`.</span><span class="sxs-lookup"><span data-stu-id="fc119-610">The following example calls `makeEwsRequestAsync` to use the `GetItem` operation to get the subject of an item.</span></span>

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