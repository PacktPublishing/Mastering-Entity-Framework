#Mastering Entity Framework

This is the code repository for [Mastering Entity Framework](https://www.packtpub.com/application-development/mastering-entity-framework?utm_source=github&utm_medium=repository&utm_campaign=9781784391003), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

##Instructions and Navigation
All of the code is organized into folders. Each folder starts with number followed by the application name. For example, 1-GuessTheNumber which is application from chapter 1.

Each Chapter contains lots of code. You will see code something similler to the following:
```
<edmx:ConceptualModels>
	<Schema Namespace="ToDoDBModel" Alias="Self" annotation:UseStrongSpatialTypes="false" xmlns:annotation="http://schemas.microsoft.com/ado/2009/02/edm/annotation" xmlns="http://schemas.microsoft.com/ado/2009/11/edm">
		<EntityType Name="ToDo">
			<Key><PropertyRef Name="Id" /></Key>
			<Property Name="Id" Type="Int32" Nullable="false" />
			<Property Name="TodoItem" Type="String" MaxLength="Max" FixedLength="false" Unicode="true" Nullable="false" />
			<Property Name="IsDone" Type="Boolean" Nullable="false" />
		</EntityType>
		<EntityContainer Name="ToDoDBEntities" annotation:LazyLoadingEnabled="true">
			<EntitySet Name="ToDos" EntityType="Self.ToDo" />
		</EntityContainer>
	</Schema>
</edmx:ConceptualModels>
```
##Related Entity Framework Products:
* [Entity Framework Tutorial](https://www.packtpub.com/application-development/entity-framework-tutorial?utm_source=github&utm_medium=repository&utm_campaign=9781847195227)
* [Entity Framework 4.1: Expert’s Cookbook](https://www.packtpub.com/application-development/entity-framework-41-expert%E2%80%99s-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781849684460)
* [WCF Multi-layer Services Development with Entity Framework - Fourth Edition](https://www.packtpub.com/application-development/wcf-multi-layer-services-development-entity-framework-4th-edition?utm_source=github&utm_medium=repository&utm_campaign=9781784391041)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781784391003">https://packt.link/free-ebook/9781784391003 </a> </p>