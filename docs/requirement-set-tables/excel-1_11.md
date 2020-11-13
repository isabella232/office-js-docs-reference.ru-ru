| <span data-ttu-id="fed46-101">Класс</span><span class="sxs-lookup"><span data-stu-id="fed46-101">Class</span></span> | <span data-ttu-id="fed46-102">Поля</span><span class="sxs-lookup"><span data-stu-id="fed46-102">Fields</span></span> | <span data-ttu-id="fed46-103">Описание</span><span class="sxs-lookup"><span data-stu-id="fed46-103">Description</span></span> |
|:---|:---|:---|
|[<span data-ttu-id="fed46-104">Application</span><span class="sxs-lookup"><span data-stu-id="fed46-104">Application</span></span>](/javascript/api/excel/excel.application)|[<span data-ttu-id="fed46-105">cultureInfo</span><span class="sxs-lookup"><span data-stu-id="fed46-105">cultureInfo</span></span>](/javascript/api/excel/excel.application#cultureinfo)|<span data-ttu-id="fed46-106">Предоставляет сведения, основанные на текущих параметрах языковых параметров системы.</span><span class="sxs-lookup"><span data-stu-id="fed46-106">Provides information based on current system culture settings.</span></span>|
||[<span data-ttu-id="fed46-107">деЦималсепаратор</span><span class="sxs-lookup"><span data-stu-id="fed46-107">decimalSeparator</span></span>](/javascript/api/excel/excel.application#decimalseparator)|<span data-ttu-id="fed46-108">Получает строку, используемую в качестве десятичного разделителя для числовых значений.</span><span class="sxs-lookup"><span data-stu-id="fed46-108">Gets the string used as the decimal separator for numeric values.</span></span>|
||[<span data-ttu-id="fed46-109">саусандссепаратор</span><span class="sxs-lookup"><span data-stu-id="fed46-109">thousandsSeparator</span></span>](/javascript/api/excel/excel.application#thousandsseparator)|<span data-ttu-id="fed46-110">Получает строку, используемую для разделения групп цифр слева от десятичного разделителя для числовых значений.</span><span class="sxs-lookup"><span data-stu-id="fed46-110">Gets the string used to separate groups of digits to the left of the decimal for numeric values.</span></span>|
||[<span data-ttu-id="fed46-111">усесистемсепараторс</span><span class="sxs-lookup"><span data-stu-id="fed46-111">useSystemSeparators</span></span>](/javascript/api/excel/excel.application#usesystemseparators)|<span data-ttu-id="fed46-112">Указывает, включены ли системные разделители Excel.</span><span class="sxs-lookup"><span data-stu-id="fed46-112">Specifies if the system separators of Excel are enabled.</span></span>|
|[<span data-ttu-id="fed46-113">Comment</span><span class="sxs-lookup"><span data-stu-id="fed46-113">Comment</span></span>](/javascript/api/excel/excel.comment)|[<span data-ttu-id="fed46-114">mentions</span><span class="sxs-lookup"><span data-stu-id="fed46-114">mentions</span></span>](/javascript/api/excel/excel.comment#mentions)|<span data-ttu-id="fed46-115">Получает объекты (например, людей), которые упоминаются в комментариях.</span><span class="sxs-lookup"><span data-stu-id="fed46-115">Gets the entities (e.g., people) that are mentioned in comments.</span></span>|
||[<span data-ttu-id="fed46-116">ричконтент</span><span class="sxs-lookup"><span data-stu-id="fed46-116">richContent</span></span>](/javascript/api/excel/excel.comment#richcontent)|<span data-ttu-id="fed46-117">Получает содержимое форматированного комментария (например, упоминание в комментариях).</span><span class="sxs-lookup"><span data-stu-id="fed46-117">Gets the rich comment content (e.g., mentions in comments).</span></span>|
||[<span data-ttu-id="fed46-118">определяем</span><span class="sxs-lookup"><span data-stu-id="fed46-118">resolved</span></span>](/javascript/api/excel/excel.comment#resolved)|<span data-ttu-id="fed46-119">Состояние цепочки комментариев.</span><span class="sxs-lookup"><span data-stu-id="fed46-119">The comment thread status.</span></span>|
||[<span data-ttu-id="fed46-120">Упдатементионс (Контентвисментионс: Excel. Комментричконтент)</span><span class="sxs-lookup"><span data-stu-id="fed46-120">updateMentions(contentWithMentions: Excel.CommentRichContent)</span></span>](/javascript/api/excel/excel.comment#updatementions-contentwithmentions-)|<span data-ttu-id="fed46-121">Обновляет содержимое комментария с помощью специально отформатированной строки и списка упоминаний.</span><span class="sxs-lookup"><span data-stu-id="fed46-121">Updates the comment content with a specially formatted string and a list of mentions.</span></span>|
|[<span data-ttu-id="fed46-122">CommentCollection</span><span class="sxs-lookup"><span data-stu-id="fed46-122">CommentCollection</span></span>](/javascript/api/excel/excel.commentcollection)|[<span data-ttu-id="fed46-123">Add (Целладдресс: \| строка Range, Content: комментричконтент \| String, ContentType?: Excel. ContentType)</span><span class="sxs-lookup"><span data-stu-id="fed46-123">add(cellAddress: Range \| string, content: CommentRichContent \| string, contentType?: Excel.ContentType)</span></span>](/javascript/api/excel/excel.commentcollection#add-celladdress--content--contenttype-)|<span data-ttu-id="fed46-124">Создает новое примечание с указанным содержимым в определенной ячейке.</span><span class="sxs-lookup"><span data-stu-id="fed46-124">Creates a new comment with the given content on the given cell.</span></span>|
|[<span data-ttu-id="fed46-125">CommentMention</span><span class="sxs-lookup"><span data-stu-id="fed46-125">CommentMention</span></span>](/javascript/api/excel/excel.commentmention)|[<span data-ttu-id="fed46-126">email</span><span class="sxs-lookup"><span data-stu-id="fed46-126">email</span></span>](/javascript/api/excel/excel.commentmention#email)|<span data-ttu-id="fed46-127">Адрес электронной почты объекта, который упоминается в примечании.</span><span class="sxs-lookup"><span data-stu-id="fed46-127">The email address of the entity that is mentioned in comment.</span></span>|
||[<span data-ttu-id="fed46-128">id</span><span class="sxs-lookup"><span data-stu-id="fed46-128">id</span></span>](/javascript/api/excel/excel.commentmention#id)|<span data-ttu-id="fed46-129">Идентификатор объекта.</span><span class="sxs-lookup"><span data-stu-id="fed46-129">The id of the entity.</span></span>|
||[<span data-ttu-id="fed46-130">name</span><span class="sxs-lookup"><span data-stu-id="fed46-130">name</span></span>](/javascript/api/excel/excel.commentmention#name)|<span data-ttu-id="fed46-131">Имя объекта, который упоминается в примечании.</span><span class="sxs-lookup"><span data-stu-id="fed46-131">The name of the entity that is mentioned in comment.</span></span>|
|[<span data-ttu-id="fed46-132">CommentReply</span><span class="sxs-lookup"><span data-stu-id="fed46-132">CommentReply</span></span>](/javascript/api/excel/excel.commentreply)|[<span data-ttu-id="fed46-133">mentions</span><span class="sxs-lookup"><span data-stu-id="fed46-133">mentions</span></span>](/javascript/api/excel/excel.commentreply#mentions)|<span data-ttu-id="fed46-134">Сущности (например, люди), которые упоминаются в комментариях.</span><span class="sxs-lookup"><span data-stu-id="fed46-134">The entities (e.g., people) that are mentioned in comments.</span></span>|
||[<span data-ttu-id="fed46-135">определяем</span><span class="sxs-lookup"><span data-stu-id="fed46-135">resolved</span></span>](/javascript/api/excel/excel.commentreply#resolved)|<span data-ttu-id="fed46-136">Состояние ответа на комментарий.</span><span class="sxs-lookup"><span data-stu-id="fed46-136">The comment reply status.</span></span>|
||[<span data-ttu-id="fed46-137">ричконтент</span><span class="sxs-lookup"><span data-stu-id="fed46-137">richContent</span></span>](/javascript/api/excel/excel.commentreply#richcontent)|<span data-ttu-id="fed46-138">Содержимое форматированного комментария (например, упоминание в комментариях).</span><span class="sxs-lookup"><span data-stu-id="fed46-138">The rich comment content (e.g., mentions in comments).</span></span>|
||[<span data-ttu-id="fed46-139">Упдатементионс (Контентвисментионс: Excel. Комментричконтент)</span><span class="sxs-lookup"><span data-stu-id="fed46-139">updateMentions(contentWithMentions: Excel.CommentRichContent)</span></span>](/javascript/api/excel/excel.commentreply#updatementions-contentwithmentions-)|<span data-ttu-id="fed46-140">Обновляет содержимое комментария с помощью специально отформатированной строки и списка упоминаний.</span><span class="sxs-lookup"><span data-stu-id="fed46-140">Updates the comment content with a specially formatted string and a list of mentions.</span></span>|
|[<span data-ttu-id="fed46-141">CommentReplyCollection</span><span class="sxs-lookup"><span data-stu-id="fed46-141">CommentReplyCollection</span></span>](/javascript/api/excel/excel.commentreplycollection)|[<span data-ttu-id="fed46-142">Добавить (контент: \| строка комментричконтент, ContentType?: Excel. ContentType)</span><span class="sxs-lookup"><span data-stu-id="fed46-142">add(content: CommentRichContent \| string, contentType?: Excel.ContentType)</span></span>](/javascript/api/excel/excel.commentreplycollection#add-content--contenttype-)|<span data-ttu-id="fed46-143">Создает ответ на примечание.</span><span class="sxs-lookup"><span data-stu-id="fed46-143">Creates a comment reply for comment.</span></span>|
|[<span data-ttu-id="fed46-144">CommentRichContent</span><span class="sxs-lookup"><span data-stu-id="fed46-144">CommentRichContent</span></span>](/javascript/api/excel/excel.commentrichcontent)|[<span data-ttu-id="fed46-145">mentions</span><span class="sxs-lookup"><span data-stu-id="fed46-145">mentions</span></span>](/javascript/api/excel/excel.commentrichcontent#mentions)|<span data-ttu-id="fed46-146">Массив, содержащий все сущности (например, люди), упомянутые в комментарии.</span><span class="sxs-lookup"><span data-stu-id="fed46-146">An array containing all the entities (e.g., people) mentioned within the comment.</span></span>|
||[<span data-ttu-id="fed46-147">ричконтент</span><span class="sxs-lookup"><span data-stu-id="fed46-147">richContent</span></span>](/javascript/api/excel/excel.commentrichcontent#richcontent)|<span data-ttu-id="fed46-148">Задает расширенное содержимое комментария (например, закомментировать содержимое с упоминанием о том, что первый упомянутый объект имеет атрибут ID 0, а вторая упомянутая сущность имеет атрибут ID 1).</span><span class="sxs-lookup"><span data-stu-id="fed46-148">Specifies the rich content of the comment (e.g., comment content with mentions, the first mentioned entity has an id attribute of 0, and the second mentioned entity has an id attribute of 1).</span></span>|
|[<span data-ttu-id="fed46-149">CultureInfo</span><span class="sxs-lookup"><span data-stu-id="fed46-149">CultureInfo</span></span>](/javascript/api/excel/excel.cultureinfo)|[<span data-ttu-id="fed46-150">name</span><span class="sxs-lookup"><span data-stu-id="fed46-150">name</span></span>](/javascript/api/excel/excel.cultureinfo#name)|<span data-ttu-id="fed46-151">Получает имя языка и региональных параметров в формате languagecode2-Country/regioncode2 (например, "zh-CN" или "en-US").</span><span class="sxs-lookup"><span data-stu-id="fed46-151">Gets the culture name in the format languagecode2-country/regioncode2 (e.g., "zh-cn" or "en-us").</span></span>|
||[<span data-ttu-id="fed46-152">numberFormat</span><span class="sxs-lookup"><span data-stu-id="fed46-152">numberFormat</span></span>](/javascript/api/excel/excel.cultureinfo#numberformat)|<span data-ttu-id="fed46-153">Определяет формат отображения чисел, соответствующий культуре.</span><span class="sxs-lookup"><span data-stu-id="fed46-153">Defines the culturally appropriate format of displaying numbers.</span></span>|
|[<span data-ttu-id="fed46-154">NumberFormatInfo</span><span class="sxs-lookup"><span data-stu-id="fed46-154">NumberFormatInfo</span></span>](/javascript/api/excel/excel.numberformatinfo)|[<span data-ttu-id="fed46-155">нумбердеЦималсепаратор</span><span class="sxs-lookup"><span data-stu-id="fed46-155">numberDecimalSeparator</span></span>](/javascript/api/excel/excel.numberformatinfo#numberdecimalseparator)|<span data-ttu-id="fed46-156">Получает строку, используемую в качестве десятичного разделителя для числовых значений.</span><span class="sxs-lookup"><span data-stu-id="fed46-156">Gets the string used as the decimal separator for numeric values.</span></span>|
||[<span data-ttu-id="fed46-157">нумберграупсепаратор</span><span class="sxs-lookup"><span data-stu-id="fed46-157">numberGroupSeparator</span></span>](/javascript/api/excel/excel.numberformatinfo#numbergroupseparator)|<span data-ttu-id="fed46-158">Получает строку, используемую для разделения групп цифр слева от десятичного разделителя для числовых значений.</span><span class="sxs-lookup"><span data-stu-id="fed46-158">Gets the string used to separate groups of digits to the left of the decimal for numeric values.</span></span>|
|[<span data-ttu-id="fed46-159">Range</span><span class="sxs-lookup"><span data-stu-id="fed46-159">Range</span></span>](/javascript/api/excel/excel.range)|[<span data-ttu-id="fed46-160">moveTo (Дестинатионранже: \| строка Range)</span><span class="sxs-lookup"><span data-stu-id="fed46-160">moveTo(destinationRange: Range \| string)</span></span>](/javascript/api/excel/excel.range#moveto-destinationrange-)|<span data-ttu-id="fed46-161">Перемещает значения ячеек, форматирование и формулы из текущего диапазона в конечный диапазон, заменяя старые сведения в этих ячейках.</span><span class="sxs-lookup"><span data-stu-id="fed46-161">Moves cell values, formatting, and formulas from current range to the destination range, replacing the old information in those cells.</span></span>|
|[<span data-ttu-id="fed46-162">RangeFormat</span><span class="sxs-lookup"><span data-stu-id="fed46-162">RangeFormat</span></span>](/javascript/api/excel/excel.rangeformat)|[<span data-ttu-id="fed46-163">Аджустиндент (Amount: число)</span><span class="sxs-lookup"><span data-stu-id="fed46-163">adjustIndent(amount: number)</span></span>](/javascript/api/excel/excel.rangeformat#adjustindent-amount-)|<span data-ttu-id="fed46-164">Настраивает отступ для форматирования диапазона.</span><span class="sxs-lookup"><span data-stu-id="fed46-164">Adjusts the indentation of the range formatting.</span></span>|
|[<span data-ttu-id="fed46-165">Workbook</span><span class="sxs-lookup"><span data-stu-id="fed46-165">Workbook</span></span>](/javascript/api/excel/excel.workbook)|[<span data-ttu-id="fed46-166">close(closeBehavior?: Excel.CloseBehavior)</span><span class="sxs-lookup"><span data-stu-id="fed46-166">close(closeBehavior?: Excel.CloseBehavior)</span></span>](/javascript/api/excel/excel.workbook#close-closebehavior-)|<span data-ttu-id="fed46-167">Закрывает текущую книгу.</span><span class="sxs-lookup"><span data-stu-id="fed46-167">Close current workbook.</span></span>|
||[<span data-ttu-id="fed46-168">save(saveBehavior?: Excel.SaveBehavior)</span><span class="sxs-lookup"><span data-stu-id="fed46-168">save(saveBehavior?: Excel.SaveBehavior)</span></span>](/javascript/api/excel/excel.workbook#save-savebehavior-)|<span data-ttu-id="fed46-169">Сохраняет текущую книгу.</span><span class="sxs-lookup"><span data-stu-id="fed46-169">Save current workbook.</span></span>|
|[<span data-ttu-id="fed46-170">Worksheet</span><span class="sxs-lookup"><span data-stu-id="fed46-170">Worksheet</span></span>](/javascript/api/excel/excel.worksheet)|[<span data-ttu-id="fed46-171">онровхидденчанжед</span><span class="sxs-lookup"><span data-stu-id="fed46-171">onRowHiddenChanged</span></span>](/javascript/api/excel/excel.worksheet#onrowhiddenchanged)|<span data-ttu-id="fed46-172">Происходит при изменении скрытого состояния одной или нескольких строк на определенном листе.</span><span class="sxs-lookup"><span data-stu-id="fed46-172">Occurs when the hidden state of one or more rows has changed on a specific worksheet.</span></span>|
|[<span data-ttu-id="fed46-173">WorksheetCalculatedEventArgs</span><span class="sxs-lookup"><span data-stu-id="fed46-173">WorksheetCalculatedEventArgs</span></span>](/javascript/api/excel/excel.worksheetcalculatedeventargs)|[<span data-ttu-id="fed46-174">address</span><span class="sxs-lookup"><span data-stu-id="fed46-174">address</span></span>](/javascript/api/excel/excel.worksheetcalculatedeventargs#address)|<span data-ttu-id="fed46-175">Адрес диапазона, который выполнил вычисление.</span><span class="sxs-lookup"><span data-stu-id="fed46-175">The address of the range that completed calculation.</span></span>|
|[<span data-ttu-id="fed46-176">WorksheetCollection</span><span class="sxs-lookup"><span data-stu-id="fed46-176">WorksheetCollection</span></span>](/javascript/api/excel/excel.worksheetcollection)|[<span data-ttu-id="fed46-177">онровхидденчанжед</span><span class="sxs-lookup"><span data-stu-id="fed46-177">onRowHiddenChanged</span></span>](/javascript/api/excel/excel.worksheetcollection#onrowhiddenchanged)|<span data-ttu-id="fed46-178">Происходит при изменении скрытого состояния одной или нескольких строк на определенном листе.</span><span class="sxs-lookup"><span data-stu-id="fed46-178">Occurs when the hidden state of one or more rows has changed on a specific worksheet.</span></span>|
|[<span data-ttu-id="fed46-179">WorksheetRowHiddenChangedEventArgs</span><span class="sxs-lookup"><span data-stu-id="fed46-179">WorksheetRowHiddenChangedEventArgs</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs)|[<span data-ttu-id="fed46-180">address</span><span class="sxs-lookup"><span data-stu-id="fed46-180">address</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#address)|<span data-ttu-id="fed46-181">Получает адрес диапазона, представляющий измененную область конкретного листа.</span><span class="sxs-lookup"><span data-stu-id="fed46-181">Gets the range address that represents the changed area of a specific worksheet.</span></span>|
||[<span data-ttu-id="fed46-182">changeType</span><span class="sxs-lookup"><span data-stu-id="fed46-182">changeType</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#changetype)|<span data-ttu-id="fed46-183">Получает тип изменения, которое представляет способ запуска события.</span><span class="sxs-lookup"><span data-stu-id="fed46-183">Gets the type of change that represents how the event was triggered.</span></span>|
||[<span data-ttu-id="fed46-184">source</span><span class="sxs-lookup"><span data-stu-id="fed46-184">source</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#source)|<span data-ttu-id="fed46-185">Получает источник события.</span><span class="sxs-lookup"><span data-stu-id="fed46-185">Gets the source of the event.</span></span>|
||[<span data-ttu-id="fed46-186">type</span><span class="sxs-lookup"><span data-stu-id="fed46-186">type</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#type)|<span data-ttu-id="fed46-187">Получает тип события.</span><span class="sxs-lookup"><span data-stu-id="fed46-187">Gets the type of the event.</span></span>|
||[<span data-ttu-id="fed46-188">worksheetId</span><span class="sxs-lookup"><span data-stu-id="fed46-188">worksheetId</span></span>](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#worksheetid)|<span data-ttu-id="fed46-189">Получает идентификатор листа, в котором изменены данные.</span><span class="sxs-lookup"><span data-stu-id="fed46-189">Gets the id of the worksheet in which the data changed.</span></span>|