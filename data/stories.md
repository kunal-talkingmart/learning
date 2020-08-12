## buy no specific
*greet
 -utter_wc
*buy_services
 -utter_check_specific_service
*not_sure_check_offer
 -utter_offers_categories
*check_shopping_offer
 -utter_offer_shopping_merchants
*chose_merchant
 -utter_conclude


## buy specific
*greet
 -utter_wc
*buy_services
 -utter_check_specific_service
*check_dining_offer
 -utter_offer_dining_merchants
*check_na_merchant
 -utter_na_apologies_reoffer_dining
*chose_merchant
 -utter_conclude

## redeem for specific 
*greet
 -utter_wc
*redeem_points
 -utter_check_specific_service
*check_spa_offer
 -utter_offer_spa_merchants
*chose_merchant
 -utter_conclude

## redeem for non  specific 
*greet
 -utter_wc
*redeem_points
 -utter_check_specific_service
*not_sure_check_offer
 -utter_offers_categories


## redeem -chat
*greet
 -utter_wc
*redeem_points
 -utter_check_specific_service
*chat_rep
 -utter_ask_name
*name_provided
 -utter_greet_ask_email
*email_provided
 -utter_trasfer
