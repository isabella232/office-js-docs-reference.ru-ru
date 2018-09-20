# <a name="appdomains-element"></a><span data-ttu-id="50aa5-101">Элемент AppDomains</span><span class="sxs-lookup"><span data-stu-id="50aa5-101">AppDomains element</span></span>

<span data-ttu-id="50aa5-p101">Определяет все домены, кроме указанного в элементе SourceLocation, которые надстройка Office будет использовать для загрузки страниц. Для каждого дополнительного домена укажите элемент AppDomain.</span><span class="sxs-lookup"><span data-stu-id="50aa5-p101">Lists any domains in addition to the domain specified in the SourceLocation element that your Office Add-in will use to load pages. For each additional domain, specify an AppDomain element.</span></span>

 <span data-ttu-id="50aa5-104">**Тип надстройки:** контентные и почтовые надстройки, надстройки области задач.</span><span class="sxs-lookup"><span data-stu-id="50aa5-104">**Add-in type:** Content, Task pane, Mail</span></span>

## <a name="syntax"></a><span data-ttu-id="50aa5-105">Синтаксис</span><span class="sxs-lookup"><span data-stu-id="50aa5-105">Syntax</span></span>

```XML
<AppDomains>
    <AppDomain>AppDomain1</AppDomain>
    <AppDomain>AppDomain2</AppDomain>
</AppDomains>
```

## <a name="contained-in"></a><span data-ttu-id="50aa5-106">Содержащиеся в</span><span class="sxs-lookup"><span data-stu-id="50aa5-106">Contained in</span></span>

[<span data-ttu-id="50aa5-107">OfficeApp</span><span class="sxs-lookup"><span data-stu-id="50aa5-107">OfficeApp</span></span>](officeapp.md)

## <a name="can-contain"></a><span data-ttu-id="50aa5-108">Может содержать</span><span class="sxs-lookup"><span data-stu-id="50aa5-108">Can contain</span></span>

[<span data-ttu-id="50aa5-109">AppDomain</span><span class="sxs-lookup"><span data-stu-id="50aa5-109">AppDomain</span></span>](appdomain.md)

## <a name="remarks"></a><span data-ttu-id="50aa5-110">Замечания</span><span class="sxs-lookup"><span data-stu-id="50aa5-110">Remarks</span></span>

<span data-ttu-id="50aa5-p102">По умолчанию надстройка может загружать страницы из домена, указанного в элементе **SourceLocation**. Для загрузки страниц из других доменов, укажите домены в элементах **AppDomains** и **AppDomain**. Этот элемент не может быть пустым.</span><span class="sxs-lookup"><span data-stu-id="50aa5-p102">By default, your add-in can load any page that is in the same domain as the location specified in the **SourceLocation** element. To load pages that are not in the same domain as the add-in, specify the domains by using the **AppDomains** and **AppDomain** elements. This element can't be empty.</span></span> 