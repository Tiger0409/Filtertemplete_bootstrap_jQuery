# Filtertemplete_bootstrap_jQuery
This is Filter templete use BootStrap, jQuery, Css.

# About Filtertemplete_bootstrap_jQuery

I created a template to search the data by using various filters.
It is mobile and iPad friendly.
You can use it with node, laravel, php, adminpanel

<script>
	var flag=0;
	function show(){
		if(flag==0){
			$(".hidenfield").show() 
			$("#option").text('Less Option');
			$("#filterResults").hide()
			flag=1;
			$(".container").css("height","900px");
			return;
		}
		if(flag==1){
			$(".hidenfield").hide() 
			$("#option").text('More Option');
			$("#filterResults").hide()
			$(".container").css("height","500px");
			flag=0;
			return;
		}
		
	}
	$(".hidenfield").hide() 
	
	var filterflag=0;
	function showData(){
		if(filterflag==0){
			$("#hiddenRow").show()
			$("#filterResults").show()
			$("#option").show()
			filterflag=1;
			return;
		}
		if(filterflag==1){
			
			$("#filterResults").hide()
			filterflag=0;
			return;
		}
		
	}
</script>


## Display first page
!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/1.PNG "Filtertemplete_bootstrap_jQuery Presentation")

## Click "More Option" button
!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/2.PNG "Filtertemplete_bootstrap_jQuery Presentation")

## Click "Filter" button
!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/3.PNG "Filtertemplete_bootstrap_jQuery Presentation")

## Display first page Click "More Option" button and "Filter" button
!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/4.PNG "Filtertemplete_bootstrap_jQuery Presentation")

## Mobile responsive
!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/5.PNG "Filtertemplete_bootstrap_jQuery Presentation")

!["Filtertemplete_bootstrap_jQuery Presentation"](https://github.com/Tiger0409/Filtertemplete_bootstrap_jQuery/blob/master/img/6.PNG "Filtertemplete_bootstrap_jQuery Presentation")


## I sincerely hope that your project is doing well.
