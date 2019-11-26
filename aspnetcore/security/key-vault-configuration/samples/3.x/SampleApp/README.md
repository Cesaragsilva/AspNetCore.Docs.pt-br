# <a name="key-vault-configuration-provider-sample-app"></a><span data-ttu-id="99f2f-101">Aplicativo de exemplo do provedor de configuração Key Vault</span><span class="sxs-lookup"><span data-stu-id="99f2f-101">Key Vault Configuration Provider Sample App</span></span>

<span data-ttu-id="99f2f-102">Este exemplo ilustra o uso do provedor de configuração Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="99f2f-102">This sample illustrates the use of the Azure Key Vault Configuration Provider.</span></span>

<span data-ttu-id="99f2f-103">O exemplo é executado em um dos dois modos determinados pela instrução `#define` na parte superior do arquivo *Program.cs* .</span><span class="sxs-lookup"><span data-stu-id="99f2f-103">The sample runs in one of two modes determined by the `#define` statement at the top of the *Program.cs* file.</span></span> <span data-ttu-id="99f2f-104">Para obter instruções, consulte [diretivas de pré-processador no código de exemplo](https://docs.microsoft.com/aspnet/core#preprocessor-directives-in-sample-code):</span><span class="sxs-lookup"><span data-stu-id="99f2f-104">For instructions, see [Preprocessor directives in sample code](https://docs.microsoft.com/aspnet/core#preprocessor-directives-in-sample-code):</span></span>

* <span data-ttu-id="99f2f-105">`Certificate` &ndash; demonstra o uso de uma ID de cliente do Azure Key Vault e o certificado X. 509 para acessar os segredos armazenados no Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="99f2f-105">`Certificate` &ndash; Demonstrates the use of an Azure Key Vault Client ID and X.509 certificate to access secrets stored in Azure Key Vault.</span></span> <span data-ttu-id="99f2f-106">Esta versão do exemplo pode ser executada em qualquer local, implantada no serviço Azure App ou em qualquer host capaz de servir um aplicativo ASP.NET Core.</span><span class="sxs-lookup"><span data-stu-id="99f2f-106">This version of the sample can be run from any location, deployed to Azure App Service or any host capable of serving an ASP.NET Core app.</span></span>
* <span data-ttu-id="99f2f-107">`Managed` &ndash; demonstra como usar o [identidade de serviço gerenciada](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview) do Azure para autenticar o aplicativo para Azure Key Vault com a autenticação do Azure ad sem credenciais no código ou na configuração do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="99f2f-107">`Managed` &ndash; Demonstrates how to use Azure's [Managed Service Identity](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/overview) to authenticate the app to Azure Key Vault with Azure AD authentication without credentials in the app's code or configuration.</span></span> <span data-ttu-id="99f2f-108">Uma ID de cliente e um segredo do Azure AD não são necessários para que o aplicativo seja autenticado com Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="99f2f-108">An Azure AD Client ID and Secret aren't required for the app to authenticate with Azure Key Vault.</span></span> <span data-ttu-id="99f2f-109">Este exemplo deve ser implantado no serviço Azure App para explorar a identidade gerenciada scearnio.</span><span class="sxs-lookup"><span data-stu-id="99f2f-109">This sample must be deployed to Azure App Service to explore the Managed Identity scearnio.</span></span>

<span data-ttu-id="99f2f-110">Para obter mais informações, consulte [Azure Key Vault provedor de configuração](https://docs.microsoft.com/aspnet/core/security/key-vault-configuration).</span><span class="sxs-lookup"><span data-stu-id="99f2f-110">For more information, see [Azure Key Vault Configuration Provider](https://docs.microsoft.com/aspnet/core/security/key-vault-configuration).</span></span>