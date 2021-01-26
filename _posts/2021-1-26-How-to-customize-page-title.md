---
layout: post
title: How to customize the page title in Xamarin Forms
---

This is an easy way to customize your page title by simply changing the font.

Inside a content page, you just add a TitleView and a Label inside:

```xaml

<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
             mc:Ignorable="d">

    <NavigationPage.TitleView>
        <Label FontFamily="YOUR FONT GOES HERE" Text="Page title text" />
    </NavigationPage.TitleView>

    <ContentPage.Content>
       <!-- Content goes here -->
    </ContentPage.Content>

</ContentPage>

```
