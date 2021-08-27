<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128553242/14.1.6%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T153466)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/DevExpressMvcApplication1/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/DevExpressMvcApplication1/Controllers/HomeController.vb))
* [CustomClasses.cs](./CS/DevExpressMvcApplication1/Models/CustomClasses.cs) (VB: [CustomClasses.vb](./VB/DevExpressMvcApplication1/Models/CustomClasses.vb))
* [SchedulerDataHelper.cs](./CS/DevExpressMvcApplication1/Models/SchedulerDataHelper.cs) (VB: [SchedulerDataHelper.vb](./VB/DevExpressMvcApplication1/Models/SchedulerDataHelper.vb))
* [Index.cshtml](./CS/DevExpressMvcApplication1/Views/Home/Index.cshtml)
* [SchedulerPartial.cshtml](./CS/DevExpressMvcApplication1/Views/Home/SchedulerPartial.cshtml)
<!-- default file list end -->
# How to bind MVC Scheduler to a collection of custom objects (List)


<p>This example demonstrates how to use two List instances (resources and appointments) as MVC Scheduler data sources.<br />The SchedulerDataObject class (which contains two properties: Appointments and Resources ) is used as a model for a corresponding "Scheduler" partial view. <br />CRUD operations (create, update, delete) are implemented using corresponding <strong>SchedulerExtension </strong>methods (<a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcSchedulerExtension_GetAppointmentsToInsert[T]topic3645">GetAppointmentsToInsert</a>, <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcSchedulerExtension_GetAppointmentsToUpdate[T]topic3653">GetAppointmentsToUpdate</a>, <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcSchedulerExtension_GetAppointmentsToRemove[T]topic3649">GetAppointmentsToRemove</a>) and standard List methods (Add, Remove). </p>

<br/>


