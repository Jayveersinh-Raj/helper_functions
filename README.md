# helper_functions
Helper functions for some common tasks which includes the following:
1. Return the train data from csv and a shuffled of that trained data (`preprocess_data(filename, fraction, rand_state)`)
2. Load and prepare image data (`load_and_prep_image(filename, img_shape=224, scale=True)`)
3. Plot confusion matrix (`make_confusion_matrix(y_true, y_pred, classes=None, figsize=(10, 10), text_size=15, norm=False, savefig=False)`)
4. Make predictions on image and plot them (`pred_and_plot(model, filename, class_names)`)
5. Creates a tensorboad callback (`create_tensorboard_callback(dir_name, experiment_name)`)
6. Plot loss curves (`plot_loss_curves(history)`)
7. Compare histories (`compare_historys(original_history, new_history, initial_epochs=5)`)
8. Unzip data (`unzip_data(filename)`)
9. Walthrough directory retruning the content (`walk_through_dir(dir_path)`)
10. Calculates accuracy, precision, recall and f1 score for a model (`calculate_results(y_true, y_pred)`)

